<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Minha Loja de Roupas</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }
        header {
            background: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }
        .produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .produto {
            background: #fff;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .produto img {
            width: 100%;
            border-radius: 8px;
        }
        .produto h3 {
            margin: 10px 0;
        }
        .preco {
            color: #27ae60;
            font-size: 20px;
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background: #25d366;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            background: #000;
            color: #fff;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>Minha Loja de Roupas</h1>
    <p>Estilo, qualidade e preço justo</p>
</header>

<div class="container">
    <h2>🛍️ Nossos Produtos</h2>

    <div class="produtos">

        <div class="produto">
            <img src="https://via.placeholder.com/300x300" alt="Camiseta">
            <h3>Camiseta Básica</h3>
            <p class="preco">R$ 59,90</p>
            <a class="btn" href="https://wa.me/5599999999999?text=Quero%20comprar%20a%20Camiseta%20Básica" target="_blank">
                Comprar no WhatsApp
            </a>
        </div>

        <div class="produto">
            <img src="https://via.placeholder.com/300x300" alt="Moletom">
            <h3>Moletom Premium</h3>
            <p class="preco">R$ 129,90</p>
            <a class="btn" href="https://wa.me/5599999999999?text=Quero%20comprar%20o%20Moletom%20Premium" target="_blank">
                Comprar no WhatsApp
            </a>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 - Minha Loja de Roupas</p>
</footer>

</body>
</html>
