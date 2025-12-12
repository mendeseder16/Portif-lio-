
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio - Eder Mendes de Souza</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #007acc;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
        }
        .apresentacao {
            text-align: center;
            padding: 50px 20px;
            background: #005f73;
            color: white;
        }
        .habilidades {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        .habilidade {
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 10px;
            padding: 20px;
            width: 180px;
            text-align: center;
        }
        .projetos {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
        }
        .projeto {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin: 10px;
            max-width: 300px;
            text-align: center;
            overflow: hidden;
        }
        .projeto img {
            width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #007acc;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Meu Portfólio - Eder Mendes de Souza</h1>
        <nav>
            <a href="#apresentacao">Sobre Mim</a>
            <a href="#habilidades">Habilidades</a>
            <a href="#projetos">Projetos</a>
        </nav>
    </header>

    <section id="apresentacao" class="apresentacao">
        <h2>Olá, sou Eder Mendes de Souza!</h2>
        <p>Sou desenvolvedor(a) web apaixonado(a) por criar experiências incríveis.</p>
    </section>

    <section id="habilidades" class="habilidades">
        <div class="habilidade">
            <h3>HTML5</h3>
        </div>
        <div class="habilidade">
            <h3>CSS3</h3>
        </div>
        <div class="habilidade">
            <h3>JavaScript</h3>
        </div>
        <div class="habilidade">
            <h3>React</h3>
        </div>
        <div class="habilidade">
            <h3>Node.js</h3>
        </div>
    </section>

    <section id="projetos" class="projetos">
        <div class="projeto">
            <img src="https://via.placeholder.com/300x200" alt="Site de Turismo">
            <h3>Site de Turismo</h3>
            <p>Uma plataforma para explorar e reservar destinos turísticos.</p>
        </div>
        <div class="projeto">
            <img src="https://via.placeholder.com/300x200" alt="Site de Pets">
            <h3>Site de Pets</h3>
            <p>Uma rede social para amantes de animais adoráveis.</p>
        </div>
        <div class="projeto">
            <img src="https://via.placeholder.com/300x200" alt="Contribuições na Dio">
            <h3>Contribuição em Projetos da Dio</h3>
            <p>Participei ativamente do desenvolvimento de projetos colaborativos.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Eder Mendes de Souza. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
