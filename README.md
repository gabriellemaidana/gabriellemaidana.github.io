<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa Nação</title>
    <link rel="shortcut icon" type="imagex/png" href="img/logo_barra.png">

    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <header>
        <div class="container">
            <nav>
                <ul>
                    <li><a href="#">Colchão</a></li>
                    <li><a href="#">Móveis</a></li>
                    <li><a href="#">Decoração</a></li>
                    <li><a class="logo" href="home.html">Casa Nação</a></li>
                    <li><a href="#">Outlet</a></li>
                    <li><a href="#">Banho</a></li>
                    <li><a href="#">Infantil</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="banner">
        <div class="container">
            <img class="foto1" src="img/banner.png" alt="">
            <img class="foto2" src="img/banner1.png" alt="">
            <img class="foto3" src="img/banner2.png" alt="">
        </div>
    </section>
    <section id="bloco_marrom">
        <div class="container">
            <div class="texto">
                <h3>O <i>melhor</i> sobre <b>casa</b> para você!</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <p>Phasellus suscipit diam eget faucibus tincidunt.</p>
                <p>Nam faucibus nec neque non suscipit. </p>
                <p>Fusce fringilla, enim ac scelerisque varius, nulla mi pretium tortor, at congue mauris massa at nisl.</p>
                <p>Vivamus vehicula consequat magna, et eleifend eros tempus ac.</p>
                <p>Morbi eu viverra nunc, et condimentum quam.</p>
            </div>
            <input type="button" value="Vamos Conversar!" id="botao">
        </div>
    </section>
    <section id="bloco_fotos">
        <div class="container">
            <div class="fotos">
                <img class="foto4" src="img/foto1.png" alt="">
                <img class="foto5" src="img/foto2.png" alt="">
                <img class="foto6" src="img/foto3.png" alt="">
                <img class="foto7" src="img/foto4.png" alt="">
                <img class="foto8" src="img/foto5.png" alt="">
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <h3>Casa Nação</h3>
            <ul>
                <li><a href="#">sobre  | </a></li>
                <li><a href="#">lojas  | </a></li>
                <li><a href="#">dúvidas  | </a></li>
                <li><a href="#">política de privacidade  | </a></li>
                <li><a href="#">fale conosco  | </a></li>
                <li><a href="#">blog</a></li>
            </ul>
            <div class="redes_sociais">
                <ul>
                    <li><a href=""><img src="img/twitter.png" alt=""></a></li>
                    <li><a href=""><img src="img/instagram.png" alt=""></a></li>
                    <li><a href=""><img src="img/behance.png" alt=""></a></li>
                    <li><a href=""><img src="img/facebook.png" alt=""></a></li>
                </ul>
            </div>
        </div>
    </footer>
</body>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Slab&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&display=swap');
</style>

</html>

CSS

/* font-family: 'Dancing Script', cursive;
    font-family: 'Roboto Slab', serif; */

body {
    font-family: 'Roboto Slab', serif;
}

.container {
    margin: 0 auto;
    width: 1200px;
}

a,li{
    text-decoration: none;
}

/* HEADER */

header nav ul li {
    display: inline-block;
    text-decoration: none;
}

header nav ul li a{
    font-size: 18px;
    color: #8d601a;
    margin-left: 60px;
}

header nav ul li a:hover{
    color: #d89425;
}

header nav ul li a.logo{
    font-family: 'Dancing Script', cursive;
    font-size: 50px;
}


/* BANNERS */

#banner .container .foto1 {
    width: 100%;
    margin-bottom: 30px;
}

#banner .container .foto2 {
    width: 583px;
    margin-right: 30px;
}

#banner .container .foto3 {
    width: 583px;
}

/* BLOCO MARROM */

#bloco_marrom {
    margin-top: 30px;
    width: 100%;
    background-color: #8d611a2c;
    height: 430px;
}

#bloco_marrom .texto {
    float: right;
    width: 100%;
    margin-bottom: 10px;
    margin-top: 30px;
}

#bloco_marrom .container h3 {
    color: #8d601a;
    text-align: center;
    font-size: 24px;
}

#bloco_marrom .container p {
    color: #8d601a;
    text-align: center;
    font-size: 18px;
}

#bloco_marrom .container #botao {
    display: block;
    color: #fff;
    text-align: center;
    font-size: 20px;
    padding: 10px;
    background-color: #8d601a;
    border: 1px solid #8d601a;
    margin: 0 auto;
}

#bloco_marrom .container #botao:hover {
    color: #8d601a;
    background-color: #fff;
    border: 1px solid #8d601a;
}

/* BLOCO DE FOTOS */

#bloco_fotos .container .fotos {
    margin-top: 30px;
    margin-bottom: 30px;
}

#bloco_fotos .container .fotos .foto4{
    margin-right: 30px;
    width: 675px;
    float: left;
    display: block;
}

#bloco_fotos .container .fotos .foto5{
    width: 495px;
    float: right;
    display: block;
}

#bloco_fotos .container .fotos .foto6{
    margin-top: 30px;
    margin-right: 30px;
    width: 322px;
    float: left;
    display: block;
}

#bloco_fotos .container .fotos .foto7{
    margin-top: 30px;
    margin-right: 30px;
    width: 323px;
    float: left;
    display: block;
}

#bloco_fotos .container .fotos .foto8{
    margin-top: 30px;
    width: 495px;
    float: left;
    display: block;
}

/* FOOTER */

footer {
    background-color: #8d611a2c;
    width: 100%;
    height: 300px;
    float: left;
    margin: 0 auto;
    margin-top: 30px;
}

footer .container ul {
    width: 630px;
    float: left;
    display: block;
}

footer .container ul li {
    text-decoration: none;
    display: inline-block;
}

footer .container h3 {
    font-family: 'Dancing Script', cursive;
    font-size: 38px;
    color: #8d601a;
    float: left;
    display: block;
    margin-top: 115px;
    margin-right: 80px;
}

footer .container ul li a {
    font-size: 18px;
    color: #8d601a;
    float: left;
    display: block;
    margin-top: 115px;
    margin-right: 10px;
}

footer .container ul li a:hover {
    color: #d89425;
}

footer .container .redes_sociais{
    width: 250px;
    float: right;
    display: block;
}

footer .container .redes_sociais ul li a{
    font-size: 18px;
    color: #8d601a;
    float: right;
    display: block;
    margin-top: 100px;
}
