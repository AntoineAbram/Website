<html lang="en">
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
        
        h1 {
        	font-family: 'Trebuchet', sans-serif;
        	font-size: 5em;
			font-weight: 500;
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
        <a href="Accueil">Français</a>
        <a href="CV-Anglais">CV</a>
        <a href="Enseignement-En">Teaching</a>
        <a href="Recherche-En">Research</a>
        <a href="Accueil-En">Home</a>
        <h1>Antoine&nbsp;Abram</h1>
    </div>
    <div id="container">
    	<div id="wrapper">
        	<div id="content">
        	    <p>
	I am a PhD student at UQÀM in the Laboratory of Algebra, Combinatorics, and Mathematical Computing (LACIM) under the direction of Christophe Reutenauer. 
				</p>
				<p>
	I obtained my bachelor's degree as well as my master's degree at UQÀM also under the direction of Christophe Reutenauer; you don't change a winning team!
				</p>
				<h4>
	Research interests:
				</h4>
				<p>
	My research are in enumerative and algebraic combinatorics. I have a strong interest in monoids defined by means of insertions, like the plactic monoid or the sylvester monoid, and their associated algebras.
				</p>

				<p>
	Here is a list of other topics in which I also have a great interest:<br>
					<ul style="list-style-type:disc;">
						<li>Automata, language theory and combinatorics on words;</li>
	  					<li>Coxeter groups; their arrangements of hyperplanes, root systems and associated polytopes such as permutahedrons;</li>
						<li>partially ordered sets, lattices and their associated polytopes;</li>
					</ul>
				</p>

				<h3>
				---  Being in the last year of my PhD, I am currently looking for a job for next year.  ---
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
