const express = require('express');
const path = require('path');
const { exec } = require('child_process');

const app = express();
const PORT = 3000;

app.set('view engine', 'ejs');
app.set('views', path.join(__dirname, 'views'));
app.use(express.static(path.join(__dirname, 'public')));

app.get('/', (req, res) => {
  res.render('index');
});

app.post('/start', (req, res) => {
  exec('pm2 start bot.js --name "discordbot"', (err) => {
    res.redirect('/');
  });
});

app.post('/stop', (req, res) => {
  exec('pm2 stop discordbot', (err) => {
    res.redirect('/');
  });
});

app.listen(PORT, () => {
  console.log(`Painel rodando em http://localhost:${PORT}`);
});
