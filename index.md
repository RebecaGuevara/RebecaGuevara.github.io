<!doctype html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Mi primera pagina web</title>
		<style type="text/css">
			*{
				margin: 0;
				padding: 0;
			}
			h1{
				color: darkred;
              font-size: 48px;
			}
			h2{
				color: chocolate;
				font-size: 27px;
				padding: 15px 15px 15px 0px;
			}
			h5{
				color: darkgoldenrod
			}
			header,footer,main{
				width: 960px;
				margin: 0 auto;/*Centra la caja automaticamente en horizontal*/
			}
			header,footer{
				height: 100px; 
				background-color: #ECC690;
				padding: 20px;
				text-align: center;
			}
			nav{
				height: 10px;
				padding: 20px;
				background-color: darkorange;
			}
			main{
				height: auto;
				background-color: #D4C0AB;
				padding: 20px;
			}
			section{
				background-color: bisque;
				margin: 30px;
				padding: 20px;
				border: solid 5px #C97C7D
			}
			p{
				padding: 10px;
			}
			ul{
	list-style-type: none;
	 margin: 0;
	padding: 0;
}
li {
  display: inline;
	color: #FFF;
	text-decoration: none;
	margin-right: 50px;
		</style>
		
	</head>
	<body>
		<header>
			<h1>MI PRIMERA PÁGINA WEB</h1>
		</header>
		<nav>
			<ul>
			<li><a href="index.html">Mi primera página</a></li>
			<li><a href="Listas.html">Listas</a></li>
			<li><a href="Enlaces.html">Enlaces</a></li>
			<li><a href="Frases de libros.html">Frases de Libros</a></li>
			<li><a href="Tablas.html">Tablas</a></li>
			<li><a href="Audio.html">Audio</a></li>
			<li><a href="Video.html">Video</a></li>
			<li><a href="Imagenes.html">Imágenes</a></li>
			<li><a href="Animaciones.html">Animaciones</a></li>
			<li><a href="Formularios.html">Formularios</a></li>
			<li><a href="Flexbox.html">Flexbox</a></li>
			<li><a href="DiaDeMuertos.html">Día de Muertos</a></li>
			<li><a href="Mediaqueries.html">Mediaqueries</a></li>
		</ul>
		</nav>
		<main>
			<section>
				<h2>Uso de la etiqueta párrafo</h2>
				<p>Nunc malesuada id erat sit amet sodales. Donec at velit quis sem malesuada vestibulum. Nulla congue viverra tempus. Integer ac est odio. Maecenas nec augue non ligula sollicitudin ullamcorper ut id ex. Nam eget nunc ultrices, mollis turpis et, molestie turpis.</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis. In mollis tempor nunc imperdiet vulputate.</p>
				<p>Nunc malesuada id erat sit amet sodales. Donec at velit quis sem malesuada vestibulum. Nulla congue viverra tempus. Integer ac est odio. Maecenas nec augue non ligula sollicitudin ullamcorper ut id ex. Nam eget nunc ultrices, mollis turpis et, molestie turpis.</p>
				<p>Nunc malesuada id erat sit amet sodales. Donec at velit quis sem malesuada vestibulum. Nulla congue viverra tempus. Integer ac est odio. Maecenas nec augue non ligula sollicitudin ullamcorper ut id ex. Nam eget nunc ultrices, mollis turpis et, molestie turpis.</p>
			</section>
			<section>
				<h2>Uso de la etiqueta encabezado</h2>
				<p>Ejemplo de la jerarquía y estilo de encabezados de h1 a h6</p>
				<h1 style="color: black; font-size: 24px;">Encabezado 1</h1>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum</p>
				<h2 style="color: black; font-size: 20px;">Encabezado 2</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum</p>
				<h3>Encabezado 3</h3>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum</p>
				<h4>Encabezado 4</h4>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum</p>
				<h5 style="color: black; font-size: 12px;">Encabezado 5</h5>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum</p>
				<h6>Encabezado 6</h6>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum</p>
			</section>
			<section>
				<h2>Formato de textos en HTML: Bold</h2>
				<p>Lorem ipsum dolor sit amet, <b>consectetur adipiscing elit.</b> In purus magna, varius non arcu et, <mark>condimentum pretium turpis.</mark> Nunc rutrum faucibus enim ac convallis. In mollis tempor nunc imperdiet vulputate. <i>Nunc malesuada id erat sit amet sodales. 
				Donec at velit quis sem malesuada vestibulum.</i> Nulla congue viverra tempus. Integer ac est odio. Maecenas nec augue non ligula sollicitudin ullamcorper ut id ex. <del>Nam eget nunc ultrices, mollis turpis et,</del> molestie turpis. La fórmula del agua es H<sub>2</sub>O. El teorema de Pitágoras dice que A<sup>2</sup>+B<sup>2</sup>=C<sup>2</sup> donde A y B son catetos.</p>
			</section>
			<section>
				<h2>Uso de cite y abbr</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis. La <abbr title=¨Benemérita Universidad Autónoma de Puebla¨>BUAP</abbr> es una institución que cuenta con Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis.</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis. El libro más prestigiado de Gabriel García Marquez es <cite>Crónicas de una muerte anunciada</cite>.</p>
			</section>
			<section>
				<h2>Uso de comenatarios en HTML</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis. purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis.</p>
				<!--Escribir comentario-->
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis. purus magna, varius non arcu et, condimentum pretium turpis. Nunc rutrum faucibus enim ac convallis.</p>
			</section>
		</main>
		<footer>
			<h5>Elaborado por Rebeca Guevara</h5>
		</footer>
	</body>
</html>
