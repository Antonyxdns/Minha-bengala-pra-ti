<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha pika</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 1em;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 2em;
            background-color: #fff;
        }
        h2 {
            color: #333;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .social a {
            color: #fff;
            margin: 0 0.5em;
            text-decoration: none;
        }
        .form-group {
            margin-bottom: 1em;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5em;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 0.5em;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo a minha pika</h1>
    </header>
    <nav>
        <a href="#sobre-mim">Sobre Mim</a>
        <a href="#portfolio">Portfólio</a>
        <a href="#blog">Blog</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="sobre-mim">
            <h2>Sobre Mim</h2>
            <p>Olá! Meu nome é [Seu Nome] e sou [Sua Profissão/Área de Interesse]. Tenho paixão por [Seus Interesses] e adoro compartilhar meus projetos e ideias com o mundo.</p>
        </section>
        <section id="portfolio">
            <h2>Portfólio</h2>
            <p>Aqui estão alguns dos meus trabalhos mais recentes:</p>
            <!-- Adicione exemplos do seu trabalho aqui -->
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <p>Bem-vindo ao meu blog! Aqui compartilho meus pensamentos, ideias e experiências sobre [Tópicos de Interesse].</p>
            <!-- Adicione posts de blog aqui -->
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form>
                <div class="form-group">
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="mensagem">Mensagem:</label>
                    <textarea id="mensagem" name="mensagem" rows="5" required></textarea>
                </div>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Meu Site Pessoal</p>
        <div class="social">
            <a href="https://facebook.com" target="_blank">Facebook</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
        </div>
    </footer>
</body>
</html>
