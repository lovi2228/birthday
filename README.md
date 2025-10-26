<!DOCTYPE html>
<!--[if lt IE 7]> <html class="ie lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>    <html class="ie lt-ie9 lt-ie8"> <![endif]-->
<!--[if IE 8]>    <html class="ie lt-ie9"> <![endif]-->
<!--[if gt IE 8]> <html> <![endif]-->
<!--[if !IE]><!--><html lang="es"><!-- <![endif]-->
<head>
	<title>🎂 Feliz Cumpleaños Liz 🎉</title>
	<meta charset="UTF-8" />
	<meta name="description" content="Feliz cumpleaños Liz">
	<meta name="robots" content="index, follow" />
	<meta name="keywords" content="Cumpleaños, Felicitación, Liz, Amor, Fiesta">
    <meta property="og:type" content="E-Greeting" />
    <meta property="og:image" content="favicon.ico" />
    <meta property="og:description" content="Una felicitación especial para Liz 💖">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="stylesheet.css">
	<link rel="stylesheet" type="text/css" href="loading.css">
	<link href='https://fonts.googleapis.com/css?family=Signika' rel='stylesheet' type='text/css'>
	<link rel="stylesheet/less" href="cake.less">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/less.js/2.1.0/less.min.js"></script>
</head>

<body>
	<div class="loading"></div>
	<audio class="song" controls loop>
        <source src="hbd.mp3"></source>
	    Tu navegador no admite audio, pero te mando un abrazo musical 🎵
    </audio>

    <!-- Letras flotantes (globos) -->
    <div class="balloons text-center" id="b1"><h2 style="color:#F2B300;">L</h2></div>
    <div class="balloons text-center" id="b2"><h2 style="color:#0719D4;">I</h2></div>
    <div class="balloons text-center" id="b3"><h2 style="color:#D14D39;">Z</h2></div>
    <div class="balloons text-center" id="b4"><h2 style="color:#8FAD00;">🎈</h2></div>
    <div class="balloons text-center" id="b5"><h2 style="color:#8377E4;">🎉</h2></div>
    <div class="balloons text-center" id="b6"><h2 style="color:#99C96A;">🎂</h2></div>

    <img src="Balloon-Border.png" width="100%" class="balloon-border">

	<div class="container">
		<!-- Luces -->
		<div class="row">
			<div class="col-md-2 col-xs-2 bulb-holder"><div class="bulb" id="bulb_yellow"></div></div>
			<div class="col-md-2 col-xs-2 bulb-holder"><div class="bulb" id="bulb_red"></div></div>
			<div class="col-md-2 col-xs-2 bulb-holder"><div class="bulb" id="bulb_blue"></div></div>
			<div class="col-md-2 col-xs-2 bulb-holder"><div class="bulb" id="bulb_green"></div></div>
			<div class="col-md-2 col-xs-2 bulb-holder"><div class="bulb" id="bulb_pink"></div></div>
			<div class="col-md-2 col-xs-2 bulb-holder"><div class="bulb" id="bulb_orange"></div></div>
		</div>

		<!-- Banner -->
		<div class="row">
			<div class="col-md-12 text-center">
				<img src="banner.png" class="bannar">
			</div>
		</div>

		<!-- Pastel -->
		<div class="row cake-cover">
			<div class="col-md-12 text-center">
				<div class="cake">
				  <div class="velas">
				    <div class="fuego"></div>
				    <div class="fuego"></div>
				    <div class="fuego"></div>
				    <div class="fuego"></div>
				    <div class="fuego"></div>
				  </div>
				  <div class="cobertura"></div>
				  <div class="bizcocho"></div>
				</div>
			</div>
		</div>

		<!-- Mensaje especial -->
		<div class="row message">
			<div class="col-md-12">
				<p>Hoy es un día mágico…</p>
				<p>como salido de un cuento de hadas,</p>
				<p>donde las estrellas brillan un poco más solo por ti.</p>
				<p>Un año más se abre ante ti,</p>
				<p>lleno de promesas, sueños y nuevas sonrisas.</p>
				<p><strong>Que este cumpleaños te regale:</strong></p>
				<p>la dulzura de los abrazos sinceros,</p>
				<p>la calidez de los recuerdos más lindos,</p>
				<p>y la alegría de saber cuánto te quieren.</p>
				<p>Hoy celebramos tu luz, tu ternura y tu fuerza,</p>
				<p>porque personas como tú hacen del mundo un lugar mejor.</p>
				<p>Que cada vela encendida sea un deseo cumplido,</p>
				<p>y que la vida te siga sonriendo con amor y esperanza.</p>
				<p>Gracias por ser quien eres, por tu bondad y por tu magia.</p>
				<p>Que este nuevo año te regale momentos tan bellos como un atardecer dorado.</p>
				<p>💖 ¡Feliz cumpleaños, querida Liz! 💖</p>
				<p>Con todo mi cariño, deseándote un día tan hermoso como tu alma.</p>
			</div>
		</div>

		<!-- Botones -->
		<div class="navbar navbar-fixed-bottom">
			<div class="row">
				<div class="col-md-6 text-center col-md-offset-3">
					<button class="btn btn-primary" id="turn_on">Encender luces</button>
					<button class="btn btn-primary" id="play">Reproducir música</button>
					<button class="btn btn-primary" id="bannar_coming">Decorar 🎊</button>
					<button class="btn btn-primary" id="balloons_flying">Soltar globos 🎈</button>
					<button class="btn btn-primary" id="cake_fadein">Mostrar pastel 🎂</button>
					<button class="btn btn-primary" id="light_candle">Encender velas 🕯️</button>
					<button class="btn btn-primary" id="wish_message">Feliz Cumpleaños</button>
					<button class="btn btn-primary" id="story">Un mensaje para ti 💌</button>
				</div>
			</div>
		</div>
	</div>

	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js"></script>
	<script src="effect.js"></script>
</body>
</html>

