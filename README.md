<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Laboratorio Creativo, scarpe personalizzate, candele personalizzate, natale, servizio Fotografico">
    <link rel="icon" href="img/favicon384x384.png">
    <link rel="stylesheet" href="styles/nav-foot.css">
    <link rel="stylesheet" href="styles/home.css">
    <link rel="stylesheet" href="styles/carousel.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800&family=Roboto:wght@100;300;400;500;700;900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@100;200;300;400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
    <title>Laboratorio Creativo</title>
</head>

<body>
    <nav class="navbar">
        <a href="home.html"><img class="logo" src="../img/logo black.png" alt="logo"></a>
        <ul class="list">
            <li>
                <a href="../html/scarpe.html"><img class="iconNav shoes" src="img/iconsNav/sneakers.png" alt="scarpe"></a>
            </li>
            <li>
                <a href="../html/candele.html"><img class="iconNav" src="img/iconsNav/candle.png" alt="candela"></a>
            </li>
            <li>
                <a href="../html/natale.html"><img class="iconNav" src="img/iconsNav/centro tavola.png" alt="Centro Tavola"></a>
            </li>
            <li>
                <a href="../html/photoBook.html"><img class="iconNav" src="img/iconsNav/camera (1).png" alt="Camera"></a>
            </li>
            <li>
                <a href="../html/spazioIdea.html"><img class="iconNav" src="img/iconsNav/giftbox.png" alt="Altro"></a>
            </li>
        </ul>
    </nav>
    <div class="aboutContainer">
        <img class="logoyellow" src="../img/logo yellow.png" alt="logo">
        <p class="about about0">Entra nel mondo della personalizzazione, navigando le pagine di questo sito troverai tante idee per meravigliosi regali.</p>
        <p class="about about1">Cammina con stile con meravigliose scarpe personalizzate, divertiti a giocare con svariati colori e infiniti temi che più ti rispecchiano.</p>
        <p class="about about2">In occasione di un evento importante stupisci con un regalo alternativo personalizzato, come le candele in cera decorate a mano.</p>
        <p class="about about3">A Natale decoriamo le vostre case con stupendi manufatti natalizi come centrotavola, portafoto e finti camini d'arredo.</p>
        <div class="carousel">
            <div class="circleButtons">
                <ul class="dotContainer">
                    <li class="dotControl dot0"></li>
                    <li class="dotControl dot1"></li>
                    <li class="dotControl dot2"></li>
                    <li class="dotControl dot3"></li>
                </ul>
            </div>
        </div>
    </div>
    <div class="gridContainer">
        <a class="anchorSection" href="../html/scarpe.html">
            <div class="sections">
                <section>
                    <img class="metro" src="img/sezione scarpe.jpg" alt="Scarpe">
                </section>
                <div class="desContainer">
                    <p class="des">Scarpe</p>
                </div>
            </div>
        </a>
        <a class="anchorSection" href="../html/candele.html">
            <div class="sections">
                <section><img src="img/sezione candele.jpg" alt="Candele"></section>
                <div class="desContainer">
                    <p class="des">Candele</p>
                </div>
            </div>
        </a>
        <a class="anchorSection" href="../html/natale.html">
            <div class="sections">
                <section><img src="img/sezione centrotavola.jpg" alt="Centro tavola"></section>
                <div class="desContainer">
                    <p class="des">Speciale Natale</p>
                </div>
            </div>
        </a>
        <a class="anchorSection" href="../html/photoBook.html">
            <div class="sections">
                <section><img src="img/sezione altro.jpg" alt="Foto Book"></section>
                <div class="desContainer">
                    <p class="des">Servizio Fotografico</p>
                </div>
            </div>
        </a>
        <a class="anchorSection" href="../html/spazioIdea.html">
            <div class="sections idea">
                <section><img src="img/altro.jpg" alt="Foto Book"></section>
                <div class="desContainer">
                    <p class="des">Spazio Idea</p>
                </div>
            </div>
        </a>
    </div>
    <footer>
        <div class="footerAbout">
            <div>
                <h2 class="contatti">Seguici su</h2>
                <div class="social">
                    <a href="https://www.facebook.com/Laboratorio-Creativo-Artistico-106594717366516/"><i class="fab fa-facebook footIco"></i></a>
                    <a href="https://instagram.com/laboratorio_creativo_art?igshid=1s8t9r77esaqu"><i class="fab fa-instagram footIco"></i></a>
                </div>
            </div>
            <div>
                <h2 class="contatti">Contattaci</h2>
                <div class="social">
                    <a href="https://api.whatsapp.com/send?phone=393311654417"><i class="fab fa-whatsapp footIco"></i></a>
                    <i class="far fa-envelope footIco"></i>
                </div>
            </div>
            <div class="chiSiamo">
                <h2 class="contatti cs">Chi Siamo</h2>
                <a href="../html/about.html"><img class="logoAbout footIco" src="img/logoAbout.png" alt="Logo"></a>
            </div>

        </div>
        <div>
            <p class="madeBy"> website by &#9679; Raffaele Di Martino</p>
        </div>
    </footer>
    <script src="../js/carousel.js"></script>
</body>

</html>
