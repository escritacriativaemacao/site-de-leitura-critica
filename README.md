<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seu Nome | Consultoria Literária</title>
    <style>
        :root {
            --primary: #2c3e50; /* Azul escuro profissional */
            --accent: #d4a373;  /* Tom de papel/ouro velho */
            --bg: #f8f9fa;
            --text: #333;
        }

        body {
            font-family: 'Georgia', serif; /* Fonte com serifa para ar literário */
            line-height: 1.6;
            margin: 0;
            color: var(--text);
            background-color: var(--bg);
        }

        header {
            background: white;
            padding: 2rem 10%;
            text-align: center;
            border-bottom: 3px solid var(--accent);
        }

        nav {
            margin-top: 1rem;
            font-family: sans-serif;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-size: 0.9rem;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: var(--primary);
            font-weight: bold;
        }

        .hero {
            padding: 4rem 10%;
            text-align: center;
            background: #fff;
        }

        .hero h1 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 1rem;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 4rem 10%;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            border-top: 4px solid var(--accent);
        }

        .about {
            background: var(--primary);
            color: white;
            padding: 4rem 10%;
        }

        .contact {
            padding: 4rem 10%;
            text-align: center;
        }

        .btn {
            background: var(--accent);
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 1rem;
            font-family: sans-serif;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 2rem;
            font-size: 0.8rem;
            background: #eee;
        }

        /* Responsividade */
        @media (max-width: 600px) {
            .hero h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>

<header>
    <div style="font-size: 1.5rem; font-weight: bold; color: var(--primary);">Escrita Criativa Em Ação</div>
    <nav>
        <a href="#servicos">Serviços</a>
        <a href="#sobre">Trajetória</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="hero">
    <h1>Transforme seu manuscrito em uma obra memorável.</h1>
    <p>Leitura crítica e consultoria em escrita criativa com foco em técnica, voz e mercado.</p>
    <a href="#contato" class="btn">Solicitar Orçamento</a>
</section>

<section id="servicos" class="services">
    <div class="service-card">
        <h3>Leitura Crítica</h3>
        <p>Análise técnica detalhada do seu livro (ritmo, personagens, furos de roteiro). Você recebe um relatório abrangente orientando os próximos passos da revisão.</p>
    </div>
    <div class="service-card">
        <h3>Consultoria de Escrita</h3>
        <p>Acompanhamento personalizado para destravar sua escrita, organizar seu projeto literário ou realizar o planejamento de mundo (worldbuilding).</p>
    </div>
</section>

<section id="sobre" class="about">
    <h2>Sobre Minha Trajetória</h2>
    <p>Renato Reis é escritor e bibliotecário, autor de "As ruínas do mundo" um romance de fantasia sombria, e "A Odisseia e o mito do retorno ao lar" uma releitura simbólica da Odisseia adaptada para o público juvenil. Além disso, ele é     um leitor voraz, apaixonado por livros e por literatura, o que o levou a se formar em biblioteconomia pelo Centro Universitário Assunção (UNIFAI). Atualmente, ele vem se dedicado ao estudo da narrativa e da arte da        escrita, prestando consultoria a outros escritores em início de carreira. </p>
</section>

<section id="contato" class="contact">
    <h2>Vamos conversar?</h2>
    <p>Para orçamentos, envie os detalhes do seu projeto (Gênero e número de caracteres).</p>
    <p><strong>Email:</strong> seuemail@exemplo.com</p>
    <a href="mailto:seuemail@exemplo.com" class="btn" style="background: var(--primary);">Enviar E-mail</a>
</section>

<footer>
    &copy; 2026 Escritacriativaemação - Consultoria Literária. Todos os direitos reservados.
</footer>

</body>
</html>
