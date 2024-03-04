<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nome do Produtor Musical</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1f1f1f;
            color: #fff;
        }

        header {
            background-color: #111;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
        }

        .hero {
            text-align: center;
            padding: 50px;
            background-color: #222;
        }

        .hero img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .latest-tracks {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .track {
            margin: 10px;
            text-align: center;
        }

        footer {
            background-color: #111;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Nome do Produtor Musical</h1>
        <p>Explorando sons inovadores</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Sobre</a>
        <a href="#">Músicas</a>
        <a href="#">Contato</a>
    </nav>

    <section class="hero">
        <img src="hero-image.jpg" alt="Produtor Musical">
        <h2>Bem-vindo ao Mundo da Música</h2>
        <p>Descubra novos sons e vibrações.</p>
    </section>

    <section class="latest-tracks">
        <div class="track">
            <h3>Última Faixa 1</h3>
            <audio controls>
                <source src="track1.mp3" type="audio/mp3">
                Seu navegador não suporta o elemento de áudio.
            </audio>
        </div>
        <div class="track">
            <h3>Última Faixa 2</h3>
            <audio controls>
                <source src="track2.mp3" type="audio/mp3">
                Seu navegador não suporta o elemento de áudio.
            </audio>
        </div>
        <!-- Adicione mais faixas conforme necessário -->
    </section>

    <footer>
        <p>&copy; 2024 Nome do Produtor Musical. Todos os direitos reservados.</p>
    </footer>

</body>

</html
