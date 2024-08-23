<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campanha Vereador Flexa</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
        }
        .menu-container {
            width: 100%;
            background-color: white;
            padding: 20px 0;
            box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .menu-container ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 40px;
        }
        .menu-container ul li {
            position: relative;
        }
        .menu-container ul li a {
            text-decoration: none;
            color: #bc8a5e;
            font-weight: bold;
            font-size: 16px;
            padding: 5px 0;
            transition: color 0.3s;
        }
        .menu-container ul li a:hover {
            color: #e64a19;
        }
        .menu-container ul li.active a {
            color: #e64a19;
        }
        .menu-container ul li.active a::after,
        .menu-container ul li a:hover::after {
            content: '';
            position: absolute;
            left: 0;
            right: 0;
            bottom: -5px;
            height: 3px;
            background-color: #e64a19;
        }
        .container {
            text-align: center;
            width: 100%;
            padding: 10px;
            box-sizing: border-box;
            margin-top: 20px;
            flex-grow: 1;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        img {
            width: 100%;
            height: auto;
            max-width: 600px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-top: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            width: 100%;
            box-sizing: border-box;
            text-align: center;
        }
        h2 {
            margin-top: 0;
        }
        p {
            margin: 0 0 10px;
            line-height: 1.6;
        }
        .social-icons {
            margin-top: 20px;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .social-icons a {
            display: inline-block;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 2px solid #bc8a5e;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            color: #bc8a5e;
            transition: background-color 0.3s, transform 0.3s;
        }
        .social-icons a:hover {
            background-color: #f5f5f5;
            transform: scale(1.1);
        }
        @media (max-width: 600px) {
            .menu-container ul {
                flex-direction: column;
                gap: 20px;
            }
            .menu-container ul li a {
                font-size: 14px;
            }
            .container {
                margin-top: 60px;
            }
            .section {
                padding: 15px;
            }
            .social-icons a {
                width: 40px;
                height: 40px;
                font-size: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="menu-container">
        <ul>
            <li class="active"><a href="#sobre">Sobre</a></li>
            <li><a href="#contato">Fale Conosco</a></li>
        </ul>
    </div>

    <div class="container">
        <img src="WhatsApp Image 2024-08-16 at 02.22.55.jpeg" alt="Campanha Vereador Flexa">
    </div>

    <div id="sobre-mim" class="section">
        <h2>Sobre Mim</h2>
        <p>
            Meu nome é Flexa, e estou me candidatando a vereador com a missão de representar nossa comunidade de forma justa e transparente. Com anos de experiência em causas sociais e engajamento comunitário, acredito que juntos podemos fazer a diferença e construir um futuro melhor para todos. Meu compromisso é com a verdade, a justiça e a melhoria da qualidade de vida de nossa cidade.
        </p>
    </div>

    <div id="contato" class="section">
        <h2>Contato</h2>
        <p>
            Se você deseja entrar em contato comigo, fique à vontade para enviar um e-mail para:
            <a href="mailto:contato@vereadorflexa.com">contato@vereadorflexa.com</a> ou ligue para (11) 98765-4321.
        </p>
        <p>
            Você também pode me seguir nas redes sociais:
        </p>
        <div class="social-icons">
            <a href="https://www.facebook.com/vereadorflexa" target="_blank">
                <i class="fab fa-facebook-f"></i>
            </a>
            <a href="https://www.instagram.com/falaflexa/" target="_blank">
                <i class="fab fa-instagram"></i>
            </a>
            <a href="https://www.whatsapp.com/vereadorflexa" target="_blank">
                <i class="fab fa-whatsapp"></i>
            </a>
        </div>
    </div>
</body>
</html>
