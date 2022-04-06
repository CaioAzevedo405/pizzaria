<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pizza-Line</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Rubik+Glitch&family=Rubik+Wet+Paint&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=DM+Sans:ital,wght@1,500&family=Rubik+Glitch&family=Rubik+Wet+Paint&display=swap');

        body {
            margin: 0;
            background-image: url(https://cdn.pixabay.com/photo/2020/03/25/21/05/pizza-4968645_960_720.jpg);
            background-repeat: no-repeat;
            background-size: 156%;
            background-position: center;
            overflow-x: hidden;
        }

        .cabecalho {
            display: flex;
            align-items: center;
            background-color: rgba(27, 27, 27, 0.541);
            padding: 20px;
            justify-content: space-around;
        }

        .links {
            display: inline-block;
            margin: 10px;
        }

        .redes-sociais {
            display: inline-block;
            margin: 20px;
        }

        .links>a {
            color: aliceblue;
            text-decoration: none;
            font-family: 'DM Sans', sans-serif;
            font-size: 15px;
        }

        .links>a:hover {
            background-color: rgba(86, 120, 145, 0.295);
            padding: 20px;
            border-radius: 15px;
            transition: 0.7s;
        }

        .redes-sociais>a:hover {
            background-color: rgba(86, 120, 145, 0.295);
            padding: 22px;
            border-radius: 15px;
            transition: 1s;
        }

        .pizza {

            font-family: 'Rubik Glitch', cursive;
            padding: 10px;
            font-size: 26px;
            color: rgb(199, 199, 196);
            text-align: center;
            overflow: hidden;
        }

        .cardapio {
            margin: 330px;
            padding: 10px;
        }

        .pizzas {
            color: aliceblue;
            display: inline-block;
            font-family: 'DM Sans', sans-serif;
            background-color: rgba(24, 26, 26, 0.459);
            width: 500px;
            padding: 15px;

        }

        .pi {
            text-align: center;
            border-radius: 10px;
        }

        .pi>h2 {
            font-family: 'DM Sans', sans-serif;
            color: rgb(199, 199, 196);
            font-size: 28px;
        }

        .btn {
            width: 200px;
            height: 30px;
            border-radius: 5px;
            border-top: none;
            border-left: none;
            background-color: rgba(90, 145, 35, 0.466);
            border-style: 2px;
            font-family: 'DM Sans', sans-serif;
            color: rgb(233, 237, 241);
        }

        .btn:hover {
            background-color: rgba(69, 185, 147, 0.486);
            transition: 0.7s;
        }

        .fim {
            background-color: rgba(0, 0, 0, 0.623);
            padding: 60px;
            color: white;
            font-family: 'DM Sans', sans-serif;
            font-size: 13px;
            text-align: center;
        }
    </style>
</head>

<body>
    <header class="cabecalho">
        <img src="logo.png" alt="logo" width="200" height="140">

        <nav class="menu">
            <ul>
                <li class="links"><a href="pizzaria.html">Home</a></li>
                <li class="links"><a href="link1.html">Sobre nós</a></li>
                <li class="links"><a href="link2.html">Contato</a></li>
            </ul>
        </nav>

        <nav class="redes">
            <ul>
                <li class="redes-sociais"><a href="https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwiBusmGlvn2AhULEpEKHcW7CIMYABAAGgJjZQ&ae=2&ohost=www.google.com&cid=CAASJORopfADwEli3Kwws1znjoc5iEWVrXdyDhooP_uZMEuekkNT_Q&sig=AOD64_3O2rC1sJZB8swPlurvBZMEv9fgMg&q&adurl&ved=2ahUKEwjktLmGlvn2AhXwLLkGHfKEAD4Q0Qx6BAgDEAE"><img src="facebook.png" alt="facebook" width="20" height="20"></a></li>
                <li class="redes-sociais"><a href="https://www.instagram.com/"><img src="instagram.png" alt="instagram" width="20" height="20"></a></li>
                <li class="redes-sociais"><a href="https://twitter.com/login?lang=pt"><img src="twitter.png" alt="twitter" width="20" height="20"></a></li>
            </ul>
        </nav>
    </header>

    <aside class="cardapio">
        <ul>
            <li class="pizza">As melhores pizzas da cidade</li>
            <li class="pizza">Deliciosas e irresistiveis</li>
            <li class="pizza">Preços Baixos</li>
        </ul>
    </aside>

    <main class="pi">
        <h2>Cardápio</h2>
        <article class="pizzas">
            <h3>Três queijos</h3>
            <img src="pizza1.png" alt="pizza" width="250" height="250"><br>
            <button class="btn">Comprar</button>
        </article>

        <article class="pizzas">
            <h3>Portuguesa</h3>
            <img src="pizza2.png" alt="pizza" width="250" height="250"><br>
            <button class="btn">Comprar</button>
        </article>

        <article class="pizzas">
            <h3>Pepperoni</h3>
            <img src="pizz3.png" alt="pizza" width="250" height="250"><br>
            <button class="btn">Comprar</button>
        </article>
    </main><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

    <footer class="fim">
        <h4>Copyright 2022</h4>

        <p>Endereço: Av. de Cillo, 2756 - Jardim Sao Jose, Americana - SP, 13467-600<br>
            Horas:
            Fechado ⋅ Abre às 18:00<br>
            Telefone: (19) 3648-0304</p>
    </footer>
</body>

</html>
