<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghost Solutions</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #0e0e1a;
            color: white;
        }

        header {
            background-color: #0e0e1a;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            border-bottom: 1px solid #222;
        }

        header h1 {
            color: #ffffff;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
        }

        .hero h2 {
            font-size: 32px;
        }

        .hero h2 span {
            color: #7f92ff;
        }

        .hero p {
            color: #ccc;
        }

        .btn {
            background-color: #7f92ff;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
        }

        section {
            padding: 40px 20px;
            border-bottom: 1px solid #222;
        }

        .section-title {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .features {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .feature {
            background-color: #1a1a2e;
            padding: 15px;
            border-radius: 8px;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #888;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            .features {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Ghost <span style="color:#7f92ff;">Solutions</span></h1>
    <nav>
        <a href="#">Início</a>
        <a href="#">Planos</a>
        <a href="#">Discord</a>
        <a href="#" style="background:#7f92ff; padding:8px 12px; border-radius:6px;">Acessar Painel</a>
    </nav>
</header>

<div class="hero">
    <h2>Encontre o seu bot <span>perfeito.</span></h2>
    <p>A solução ideal para transformar o seu servidor Discord em uma ferramenta poderosa e eficiente.</p>
    <a href="#" class="btn">Ver os nossos planos</a>
</div>

<section>
    <h3 class="section-title">Proteja sua comunidade com verificação inteligente</h3>
    <p>Nossa solução de verificação avançada garante que apenas membros legítimos tenham acesso ao seu servidor.</p>
    <div class="features">
        <div class="feature">
            <h4>🔒 Autenticação Avançada</h4>
            <p>Sistema sofisticado que rastreia IPs e impede contas falsas.</p>
        </div>
        <div class="feature">
            <h4>🎨 Design Personalizado</h4>
            <p>Adapte o visual da verificação para combinar com sua marca.</p>
        </div>
    </div>
</section>

<section>
    <h3 class="section-title">Transforme seu servidor em uma máquina de vendas automática</h3>
    <p>Automatize todo o processo de vendas, desde o atendimento até a entrega.</p>
    <div class="features">
        <div class="feature">
            <h4>🤖 Automação Total</h4>
            <p>Configure uma vez e deixe o bot cuidar de tudo.</p>
        </div>
        <div class="feature">
            <h4>📊 Análise Detalhada</h4>
            <p>Veja relatórios completos de vendas e comportamento dos clientes.</p>
        </div>
    </div>
</section>

<section>
    <h3 class="section-title">Impulsione o crescimento da sua comunidade de forma autêntica</h3>
    <p>Conquiste membros reais e interessados no seu conteúdo.</p>
    <div class="features">
        <div class="feature">
            <h4>👥 Usuários Autênticos</h4>
            <p>Conecte pessoas reais com interesses genuínos.</p>
        </div>
        <div class="feature">
            <h4>📈 Crescimento Estratégico</h4>
            <p>Aumento gradual e orgânico da sua comunidade.</p>
        </div>
    </div>
</section>

<footer>
    <p>Termos de Serviço | Discord | Youtube</p>
    <p>© 2025 Ghost Solutions. Todos os direitos reservados.</p>
</footer>

</body>
</html>