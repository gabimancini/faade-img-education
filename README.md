# faade-img-education

Una forma divertida de aprender los animales en inglés a través de sus nombres e imágenes escondidas. Colocando el puntero sobre cada palabra descubrirás el animal correspondiente.
Diseño programado en HTML y CSS. Sencillo y práctico para aplicar en diversos ámbitos educativos.

A través de dos imágenes superpuestas y la etiqueta "transition", logramos disipar la imagen de arriba y ver la que está debajo. De esta manera podremos enseñar a los niños los nombres de animales y todo lo que se nos ocurra en cualquier idioma.

También, podrán ejercitar la memoria tratando de recordar la ubicación de cada animal.
<HTML lang="es">
    <HEAD>
        <TITLE>Título de la página</TITLE>
     <meta charset="utf-8" />
	 <style type="text/css">
	 
	 header{position:relative;}
	  
	  #container{
	  margin: 5% 10%;
  position:absolute;}
  
	 .box{ 
	 width:200px;
	 display: inline-block;
	 height:200px;
	 background:#ffa500;
	   position:relative;
	   padding:3px;
	   }
	 
	 .box img {
 position:absolute;
 width:200px;
 height:200px;
  -webkit-transition: opacity 1s ease-in-out;
  -moz-transition: opacity 1s ease-in-out;
  -o-transition: opacity 1s ease-in-out;
  transition: opacity 1s ease-in-out;
}

 img.top:hover {
  opacity:0;
  width:200px;
 height:200px;
}
	 
	 </style>
    </HEAD>

    <BODY>
        <header>

	 	<h1>ANIMAL NAMES</h1>
		</header>
		<section>
		 <div id="container">
	 
  <div class="box"><img class="bottom" src="tortuga.jpg"  > 
 <img class="top"src="turtletitulo.jpg" ></div>
   
    <div class="box"><img class="bottom" src="lion.jpg" > 
   <img class="top"src="liontitulo.jpg" ></div>
   
    <div class="box"><img class="bottom" src="bee.jpg" > 
   <img class="top"src="beetitulo.jpg" ></div>
   
    <div class="box"><img class="bottom" src="elephant.jpg"  > 
   <img class="top"src="elephanttitulo.jpg"  ></div>
   
   <div class="box"><img class="bottom" src="monkey.jpg"  > 
   <img class="top"src="monkeytitulo.jpg"  ></div> 
   
   <div class="box"><img class="bottom" src="frog.jpg" > 
   <img class="top"src="frogtitulo.jpg" ></div>
   
    <div class="box"><img class="bottom" src="hippo.jpg" > 
   <img class="top"src="hippotitulo.jpg" ></div>
   
    <div class="box"><img class="bottom" src="chicken.jpg" > 
   <img class="top"src="chickentitulo.jpg" ></div>
   
    <div class="box"><img class="bottom" src="zebra.jpg" > 
   <img class="top"src="zebratitulo.jpg" ></div>
    <div class="box"><img class="bottom" src="giraffe.jpg" > 
   <img class="top"src="giraffetitulo.jpg" ></div>
   
   </div>
     
		</section>
		 
    </BODY>
</HTML>

Líneas de códigos simples en HTML y CSS. 
Visita y juega en 


