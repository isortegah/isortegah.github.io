---
layout: post
title:  "POC flow CI/CD Github and Jenkins"
date:   2021-02-25 09:50:12 -0500
categories: poc
permalink: /pocs/poc-flow-ci.html
excerpt_separator: <!--more-->
label: poc
---
<link rel="stylesheet" href="{{ "/assets/css/post.css" | relative_url }}">
<div class = "post-page">
	<div class = "p">
<h3>Motivación</h3>
<br>
Revisando un flujo de ejecución de un componente desde Jenkins que genera un reporte,
quise revisar como poder emular esta forma de trabajo, para lo cual utilizo este <a href="https://github.com/isortegahlabs/scala_and_java">proyecto</a> como base.
<!--more-->
<br><br>
<h4> Descripción</h4>
En este <b class="bold"><i class="italic">POC</i></b> se está utilizando las siguientes tecnologías: 
<br><br>
<ul class="list">
<li>
<b class="bold">Maven:</b> Administración de dependencias y gestión del proyecto.
</li>
<li><b class="bold">Scala and Java:</b> Lenguajes de programación, busco posteriormente agregar funcionalidad que me
  permíta probar la interacción entre componentes creados por <i class="italic">Scala</i> y usados en <i class="italic">Java</i> y viceversa.</li>
<li><b class="bold">Actions de Github:</b> Como parte del flujo, en github se almacenara además del código, el jar que resulta 
del empaquetado para ser consumido como dependencia y se publica el <i class="italic">release</i> que  posteriormente sera descargado desde Jenkins y ejecutado.</li>
</ul>
  
El flujo implementado es el siguiente:
<br>
<br>
<img src="/assets/imgs/pocs/ScalaAndJava.png">
<br>
<br>
<ul class="list">
<li>Los cambios al programa se suben al repositorio.</li>
<li>Github detecta los archivos de configuración de <i class="italic">Actions</i> y ejecuta el flujo de CI.</li>
<li>El flujo configurado para este proyecto, genera el package y lo pública en el servicio de <i class="italic">package</i> de Github.</li>
<li>Posterior al paso anterior se toma el <i class="italic">jar</i> generado durante el <i class="italic">mvn package</i> y se adjunta a un release.</li>
<li>En Jenkins se cuenta con un Job DSL que tira de otro repo para obtener las configuraciones de los jobs y crearlos de forma automática.</li>
<li>Ya con el job creado y configurado, al ejecutarlo esta programado para obtener el último release y ejecutarlo.  </li>
</ul>

<h4>Video demostración</h4>
<div class="imgPost">
    <a href="https://youtu.be/1nz3JywqvlI">
    <img src="https://img.youtube.com/vi/1nz3JywqvlI/0.jpg"></a>
</div>
<br><br>
<a href="https://github.com/isortegahlabs/scala_and_java">Repositorio</a>
<br><br>




    </div>

<br>
</div>
<br>
[Siguiente]({{ page.next.url }})