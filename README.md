<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VCConcursos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #004d00;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        nav {
            background-color: #333;
            color: white;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
        }
        .news, .products {
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>VCConcursos</h1>
    <p>Notícias sobre Concursos e Produtos Exclusivos</p>
</header>

<nav>
    <a href="#news">Notícias</a>
    <a href="#products">Produtos</a>
    <a href="#contact">Contato</a>
</nav>

<div class="container">
    <section id="news" class="news">
        <h2>Últimas Notícias sobre Concursos</h2>
        <p>Fique por dentro das últimas novidades sobre concursos públicos.</p>
        <!-- Aqui você pode adicionar notícias dinâmicas futuramente -->
    </section>

    <section id="products" class="products">
        <h2>Produtos</h2>
        <p>Confira nossos produtos exclusivos para ajudar na sua preparação.</p>
        <!-- Aqui você pode adicionar os produtos que deseja vender -->
    </section>
</div>

<footer>
    <p>&copy; 2024 VCConcursos. Todos os direitos reservados.</p>
</footer>

</body>
</html>
