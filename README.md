<!DOCTYPE html>
<html lang="pl-PL">
<head>
    <meta charset="UTF-8">
    <title>Portfolio Sylwia Podolewska</title>
<link href="style.css" rel="stylesheet" type="text/css" media="screen"/>
</head >
<body>
<div id="container">

    <ul id="nav">
        <li><a href="portfolio.html">Strona Główna</a></li>
        <li><a href="about.html">O mnie</a></li>
        <li><a href="projects.html">Projekty</a></li>
        <li><a href="contact.html">Kontakt</a></li>
    </ul>
    </div>

<div id="header">
    <h1>Sylwia Podolewska</h1>
    <h2>Co robię i kim jestem - czyli kilka informacji o mnie</h2>
    <p id="JA"><a href="#"><img src="DSC_1510.png" alt="oto ja" width="350" height="450"/></a></p>
    </div>

       <div id="footer">
        <p id="copyright">&copy; Sylwia Podolewska</p>
        </div>


</body>
</html>

<!DOCTYPE html>
<html lang="pl-PL">
<head>
    <meta charset="UTF-8">
    <title>O mnie</title>
    <link href="style.css" rel="stylesheet" type="text/css" media="screen"/>
</head>
<body>
<div id="header" class="page">
    <p><a href="portfolio.html">Strona Główna</a></p>
    <h1>O mnie</h1>
</div>
<div id="content" class="page"> Nazywam sie Sylwia Podolewska i dopiero rozpoczynam moją przygodę z programowaniem. <p>Z wykształcenia jestem
geografem, zawodowo związana jestem z firmą zajmującą się tworzeniem systemów dla logistyki</p>
</div>
</body>
</html>


<!DOCTYPE html>
<html lang="pl-PL">
<head>
    <meta charset="UTF-8">
    <title>Kontakt</title>
    <link href="style.css" rel="stylesheet" type="text/css" media="screen"/>
</head>
<body>
<div id="header" class="page">
    <p><a href="portfolio.html">Strona Główna</a></p>
<h1>Kontakt</h1>
</div>
<div id="content">
    <p>Chcesz się ze mną skontaktować?</p>
<p>pisz lub dzwoń!</p>
<p>509 434 298</p>
<p>sylwia.podolewska@o2.pl</p>
</div>
</body>
</html>


<!DOCTYPE html>
<html lang="pl-PL">
<head>
    <meta charset="UTF-8">
    <title>projekty</title>
    <link href="style.css" rel="stylesheet" type="text/css" media="screen"/>
</head>
<body>
<div id="header" class="page">
    <p><a href="portfolio.html">Strona Główna</a></p>
    <h1>Projekty</h1>
</div>
<div id="content">
   <a href="https://www.facebook.com/"> <img src="projekt_1.png" alt="projekt 1" width="350" height="350"> </a>
   <a href="http://poczta.o2.pl/"><img src="projekt_2.png" alt="projekt 2" width="350" height="350"></a>
</div>
</body>
</html>



body, div, h1, h2, h3, h4, h5, h6, p, ul, ol, li, dl, dt, dd, img, form, fieldset, input, textarea, blockquote {
    margin: 0;
    padding: 0;
    border: 0;
}
body{
    background: #f2f2ee; font: 16px Helvetica, Arial, Sans-Serif; color: #636363; line-height: 24px;
}
 #container {
    width: 960px; margin: 0 auto; font: 15px Georgia, Serif; color: black; letter-spacing: 2px;
 }
 #JA{
     margin: 10px auto 0 auto; position: relative; width: 183px;
 }
#header {
    height: 244px; padding: 52px 0 0 57px;
    }
#header h1{
    font: 38px Georgia, Serif; color: black; letter-spacing: 2px; margin: 0 0 20px 0;

text-shadow: 0px 1px 1px #494949;
}
#header h2{
    width: 510px; font: 30px Georgia, Serif; color: black; letter-spacing: 2px; margin: 0 0 20px 0;

    text-shadow: 0px 1px 1px #494949;
}
#footer {
    background: url(images/footer-bg.png) no-repeat; padding: 40px 0 0 0;
    overflow: hidden; margin: 0 0 30px 0;
}
#footer p#copyright {
    font-size: 12px; float: left; margin: 0 0 0 30px; color: #989693;
}
#footer p#back-top {
    font-size: 12px; float: right; margin: 0 30px 0 0;
}
#content {
    width: 1000px; font: 15px Georgia, Serif; color: black; letter-spacing: 2px; margin: 0 0 20px 0;

    text-shadow: 0px 1px 1px #494949;
}
