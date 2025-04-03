<!DOCTYPE HTML>
<html lang="fr">
<head>
    <title>Antoine Abram</title>
    <script type = "text/javascript">
          function displayNextImage() {
              x = (x === images.length - 1) ? 0 : x + 1;
              document.getElementById("img").src = images[x];
          }
          function displayPreviousImage() {
              x = (x <= 0) ? images.length - 1 : x - 1;
              document.getElementById("img").src = images[x];
          }
          function startTimer() {
              setInterval(displayNextImage, 6000);
          }
          var images = [], x = -1;
          images[0] = "Image-AntoineAbram/AntoineAbram1.jpg";
          images[1] = "Image-AntoineAbram/AntoineAbram2.jpg";
          images[2] = "Image-AntoineAbram/AntoineAbram4.jpg";
      </script>
    <style type="text/css">
        html, body {
            margin: 0;
            padding: 0;
        }
        body {
            color: #292929;
            font: 100% Roboto, Arial, sans-serif;
            font-weight: 300;
        }
        p {
            padding: 0 10px;
            line-height: 1.3;
        }
        h4 {
            margin: 0 0 -10px 0 ;
            padding: 0 10px;
            line-height: 1;
        }
        h3 {
            padding: 0 10px;
            line-height: 1;
        }
        ul li {
            padding-right: 10px;
            line-height: 1.6;
        }
        h3 {
            padding: 5px 20px;
            margin: 0;
        }
        div#container {
            width: 1300px;
            margin: 35px auto;
        }
        div#header {
            position: relative;
        }
        div#header h1 {
            text-align: center;
            height: 300px;
            line-height: 150px;
            margin: 0;
            padding: 25px 700px 25px 700px;
            background: #e0e0e0;
            color: #292929;
        }
        div#header a {
            float: right;
            top: 23px;
            padding: 10px;
            color: #006;
        }
        div#wrapper {
            float: left;
            width: 100%;
        }
        div#content {
            margin: 0 0 0 375px;
        }
        div#navigation {
            float: left;
            width: 375px;
            margin-left: -1300px;
        }
        div#navigation li {
            list-style: none;
        }
        div#extra {
            float: left;
            width: 150px;
            margin-left: -150px;
            background: #147FA9;
        }
        div#footer {
            clear: left;
            width: 100%;
            background: #42444e;
            color: #fff;
        }
        div#footer p {
            padding: 20px 10px;
        }
    </style>
</head>
<body onload = "startTimer()">
    <div id="header">
        <a href="Accueil-En">English</a>
        <a href="CV-Francais">CV</a>
        <a href="Enseignement">Enseignement</a>
        <a href="Recherche">Recherche</a>
        <a href="Accueil">Accueil</a>
        <h1>Antoine Abram</h1>
    </div>
    <div id="container">
    <div id="wrapper">
        <div id="content">
            <p>
	Je suis un étudiant au doctorat à l'UQÀM dans le Laboratoire d'Algèbre, de Combinatoire, et d'Informatique Mathématique (LACIM) sous la direction de Christophe Reutenauer.
	</p>
	<p>
	J'ai obtenu mon baccalauréat ainsi que ma maitrise à l'UQÀM aussi sous la tutelle de Christophe Reutenauer; on ne change pas une équipe gagnante!
	</p>
	<h4>
	Intérêts en recherche:
	</h4>
	<p>
	Ma recherche est principalement en combinatoire énumérative et algébrique.
	J'aime bien les monoïdes issues d'objets combinatoires, comme le monoïde plaxique ou le monoïde sylvestre et les algèbres qui y sont associées.
	</p>
	<p>
	Voici d'autres sujets pour lesquels j'ai aussi un grand intérêt:<br>
	<ul style="list-style-type:disc;">
	  <li>les automates, la théorie des langages et la combinatoire des mots;</li>
	  <li>les groupes de Coxeter; leurs arrangements d'hyperplans, systèmes de racines et les polytopes associés comme les permutohèdres;</li>
	  <li>les ensembles partiellements ordonnés, treillis et leurs polytopes associés;</li>
	</ul>
	</p>
	<h3>
	---  Étant en dernière année de doctorat, je suis présentement à la recherche d'un emploi pour l'année prochaine.  ---
	</h3>
	<p>
	Contact: abram.antoine (at) courrier.uqam.ca
	</p>
        </div>
    </div>
    <div id="navigation">
	  <img style="float:left; padding: 5px 25px 5px 20px" width="350" height="466" alt="Antoine Abram" id="img" src="Image-AntoineAbram/AntoineAbram1.jpg"/>
    </div>
</div>
<script type="text/javascript">AddFillerLink("content", "navigation", "extra")</script>
</body>
</html>
