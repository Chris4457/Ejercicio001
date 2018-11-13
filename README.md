<!DOCTYPE html>
<html>
	<!-- ================================================================================================================ -->
	<!-- Cabeza de una estructura de una página web <head> ... </head> ================================================== -->
	<!--    - Configuración base de nuestra página web y el navegador. 
		    - Enlaces a recursos externos, estilos y scripts     -->
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<title>Inicio | Mi pagina Web</title>
		<meta name="description" content="Contenido, teoría y ejercicios de la asignatura RAY - 2018">
		<meta name="author" content="G.R.P.">

		<!-- Enlaces a archivos externos que definen estilos css -->
		<link href="style/bootstrap.min.css" rel="stylesheet">
		<link href="style/font-awesome.min.css" rel="stylesheet">
		<link href="style/aniate.min.css" rel="stylesheet"> 
		<link href="style/lightbox.css" rel="stylesheet"> 
		<link href="style/main.css" rel="stylesheet">
		<link href="style/responsive.css" rel="stylesheet">

		<!--[if lt IE 9]>
			<script src="js/html5shiv.js"></script>
			<script src="js/respond.min.js"></script>
		<![endif]-->

		<!-- Enlaces a las imágenes a usar como iconos del navegador -->
		<link rel="shortcut icon" href="resources/image/ico/favicon.ico">
		<link rel="apple-touch-icon-precomposed" sizes="144x144" href="resources/image/ico/apple-touch-icon-144-precomposed.png">
		<link rel="apple-touch-icon-precomposed" sizes="114x114" href="resources/image/ico/apple-touch-icon-114-precomposed.png">
		<link rel="apple-touch-icon-precomposed" sizes="72x72" href="resources/image/ico/apple-touch-icon-72-precomposed.png">
		<link rel="apple-touch-icon-precomposed" href="resources/image/ico/apple-touch-icon-57-precomposed.png">

	</head>
	<!-- ================================================================================================================ -->


	<!-- ================================================================================================================ -->
	<!-- Cuerpo de una estructura de una página web <body> ... </body> ================================================== -->
	<!--    - Sección contenedora de todos los elementos renderizables por el navegador. 
		    - Cargas "tardías" de recursos externos -->
	<body>
		<!-- ================================================================================================================ -->
		<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
        <body background-image="file:///C:/Users/u_38016571/Desktop/1%C2%AAA3D/space-1164579_640.png">
        </body>
		<header id="header" img="file:///C:/Users/u_38016571/Desktop/1%C2%AAA3D/RAY/Deadpool-sorpresa-gif.gif" width="700" height="550">
			<div class="container">

				<div class="row">
					<div class="col-sm-12 overflow">
						<div class="social-icons pull-right">
							<ul class="nav nav-pills">
								<li><a href="https://www.facebook.com/chris.casanova.311"><i class="fa fa-facebook"></i></a></li>
								<li><a href="https://mobile.twitter.com/christi0700"><i class="fa fa-twitter"></i></a></li>
								<li><a href="https://plus.google.com/discover"><i class="fa fa-google-plus"></i></a></li>
							</ul>
						</div> 
					</div>
				</div>

			</div> <!-- div#ray-title.container -->
			<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
			<div class="navbar navbar-inverse" role="banner">
				<div class="container">

					<div class="navbar-header">
						<!-- Menú tipo botón expandible para la versión móvil -->
						<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
							<span class="sr-only">Toggle navigation</span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
						</button>
						<!-- Logo y enlace a la página de inicio -->
						<a class="navbar-brand" href="index.html">
							<h1><img src="https://sg.fiverrcdn.com/photo2s/87777731/original/23017c9b50509c7f202dce3bb3b5c28b586860af.png?1538677038" alt="logo" width="200" height="150"></h1>
						</a>
					</div>

					<!-- Barra de navegación -->
					<div class="collapse navbar-collapse">
						<ul class="nav navbar-nav navbar-right">
							<li class="active"><a href="index.html">Inicio</a></li>

							<li class="dropdown"><a href="pages/teoria.html">Teoría<i class="fa fa-angle-down"></i></a> 
								<ul role="menu" class="sub-menu">
									<li><a href="pages/tema001.html">Tema 1</a></li>
									<!--
									<li><a href="aboutus.html">About</a></li>
									<li><a href="aboutus2.html">About 2</a></li>
									<li><a href="service.html">Services</a></li>
									<li><a href="pricing.html">Pricing</a></li>
									<li><a href="contact.html">Contact us</a></li>
									<li><a href="contact2.html">Contact us 2</a></li>
									<li><a href="404.html">404 error</a></li>
									<li><a href="coming-soon.html">Coming Soon</a></li>
									-->
								</ul>
							</li>

							<li class="dropdown"><a href="pages/practicas.html">Prácticas<i class="fa fa-angle-down"></i></a>
								<ul role="menu" class="sub-menu">
									<li><a href="pages/ejercicio001.html">Ejercicios 1</a></li>

									<!--
									<li><a href="blog.html">Blog Default</a></li>
									<li><a href="blogtwo.html">Timeline Blog</a></li>
									<li><a href="blogone.html">2 Columns + Right Sidebar</a></li>
									<li><a href="blogthree.html">1 Column + Left Sidebar</a></li>
									<li><a href="blogfour.html">Blog Masonary</a></li>
									<li><a href="blogdetails.html">Blog Details</a></li>
									-->
								</ul>
							</li>

							<li class="dropdown"><a href="pages/portfolio.html">Portfolio <i class="fa fa-angle-down"></i></a>
								<ul role="menu" class="sub-menu">
									<li><a href="file:///C:/Users/u_38016571/Desktop/1%C2%AAA3D/HTML/Index2.html#">Galeria de proyectos</a></li>
									<li><a href="file:///C:/Users/u_38016571/Desktop/1%C2%AAA3D/HTML/index4.html">Curriculum</a></li>

									<!--
									<li><a href="portfoliofour.html">Isotope 3 Columns + Right Sidebar</a></li>
									<li><a href="portfolioone.html">3 Columns + Right Sidebar</a></li>
									<li><a href="portfoliotwo.html">3 Columns + Left Sidebar</a></li>
									<li><a href="portfoliothree.html">2 Columns</a></li>
									<li><a href="portfolio-details.html">Portfolio Details</a></li>
									-->
								</ul>
							</li>

							<li><a href="pages/cheetsheet.html ">Templ. CheetSheet</a></li>
						</ul>
					</div>

					<div class="search">
						<form role="form">
							<i class="fa fa-search"></i>
							<div class="field-toggle">
								<input type="text" class="search-form" autocomplete="off" placeholder="Search">
							</div>
						</form>
					</div>

				</div>

			</div> <!-- div#ray-navbar.navbar.navbar-inverse -->

			<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
		</header>
		<!--/#header - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
		<!-- ================================================================================================================ -->

		<!-- ================================================================================================================ -->
		<section id="home-slider">
			<div class="container">
				<div class="row">
					<div class="main-slider">
						<div class="slide-text">
							<h1>Christian Casanova - Diseños 3D </h1>
							<p style="color: White;"> Aprendiendo juntos los conceptos y usos de las
							 interfaces de usuario en proyectos multimedia </p>
							<a href="pages/teoria.html" class="btn btn-common">Empecemos</a>
							</div>

						<img src="http://www.periodistadigital.com/imagenes/2018/06/03/estrella-de-la-muerte_560x280.jpg" class="slider-hill" alt="slider image" width="550" height="350">
						<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3F9-9Wuklb0UMcK7E8J5hFrfo2ZhFVuEqV0ZVg2MtJD7sNu84" class="slider-house" alt="slider image" width="200" height="150">
						<img src="file:///C:/Users/u_38016571/Desktop/1%C2%AAA3D/batllespaceship.png" class="slider-birds1" alt="slider image">
						<img src="file:///C:/Users/u_38016571/Desktop/1%C2%AAA3D/batllespaceship.png" class="slider-birds2" alt="slider image">
					</div>
						</div>
					</div>
				</div>
			</div>
			<div class="preloader"><i class="fa fa-sun-o fa-spin"></i></div>
		</section>
		<!--/#home-slider-->
		<!-- ================================================================================================================ -->

		<!-- ================================================================================================================ -->
		<footer id="footer">
			<div class="container">
				<div class="row">
					<div class="col-sm-12 text-center bottom-separator">
						<img src="" class="img-responsive inline" alt="">
					</div>
					
					<div class="col-md-4 col-sm-6">
						<div class="testimonial bottom">
							<h2>Interfaces de usuario</h2>
							<div class="media">
								<div class="pull-left">
									<a href="#"><img src="" alt=""></a>
								</div>
								<div class="media-body">
									<blockquote style="color: White;">Las interfaces básicas de usuario son aquellas que incluyen cosas como menús, ventanas, teclado, ratón, y algunos otros sonidos que la computadora hace, en general, todos aquellos canales por los cuales se permite la comunicación entre el hombre y la computadora..</blockquote>
									<h3><a target="_blank" href="http://hcibib.org/tcuid/">-Lewis y Rieman (1993)</a></h3>
								</div>
							</div>
							<!--
							<div class="media">
								<div class="pull-left">
									<a href="#"><img src="resources/image/home/profile2.png" alt=""></a>
								</div>
								<div class="media-body">
									<blockquote>Capicola nisi flank sed minim sunt aliqua rump pancetta leberkas venison eiusmod.</blockquote>
									<h3><a href="">- Abraham Josef</a></h3>
								</div>
							</div> 
							-->
						</div> 
					</div>
					<div class="col-md-3 col-sm-6">
						<div class="contact-info bottom" style="color: White;">
							<h2>Contacto</h2>
							<address>
							E-mail: <a href="mailto:someone@example.com">Christian3107.ce@gmail.com</a> <br> 
							Teléfono: +34 603502867 <br> 
							</address>

							<h2>Dirección</h2>
							<address>
							Santa Cruz de Tenerife, Barrio de la Salud, <br> 
							c/Mencey Imobac, <br> 
							España <br> 
							</address>
						</div>
					</div>

					<!--
					<div class="col-md-4 col-sm-12">
						<div class="contact-form bottom">
							<h2>Send a message</h2>
							<form id="main-contact-form" name="contact-form" method="post" action="sendemail.php">
								<div class="form-group">
									<input type="text" name="name" class="form-control" required="required" placeholder="Name">
								</div>
								<div class="form-group">
									<input type="email" name="email" class="form-control" required="required" placeholder="Email Id">
								</div>
								<div class="form-group">
									<textarea name="message" id="message" required="required" class="form-control" rows="8" placeholder="Your text here"></textarea>
								</div>
								<div class="form-group">
									<input type="submit" name="submit" class="btn btn-submit" value="Submit">
								</div>
							</form>
						</div>
					</div>
					-->

					<div class="col-sm-12">
						<div class="copyright-text text-center">
							<p>CIFP César Manrique 2018.</p>
							<p>Modificación de la plantilla: <a target="_blank" href="">G.R.P.</a></p>
						</div>
					</div>
				</div>
			</div>
		</footer>
		<!--/#footer-->
		<!-- ================================================================================================================ -->

		<!-- ================================================================================================================ -->
		<!-- Carga "tardía" de librerías de scripts externos -->
		<script type="text/javascript" src="script/jquery.js"></script>
		<script type="text/javascript" src="script/bootstrap.min.js"></script>
		<script type="text/javascript" src="script/lightbox.min.js"></script>
		<script type="text/javascript" src="script/wow.min.js"></script>
		<script type="text/javascript" src="script/main.js"></script>
		<!-- ================================================================================================================ -->
	</body>
	<!-- ================================================================================================================ -->
</html>
