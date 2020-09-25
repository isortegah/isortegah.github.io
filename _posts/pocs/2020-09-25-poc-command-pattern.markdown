---
layout: post
title:  "POC Command Pattern"
date:   2020-09-25 08:50:12 -0500
categories: aop
permalink: /pocs/poc-command-pattern.html
excerpt_separator: <!--more-->
---
<link rel="stylesheet" href="{{ "/assets/css/post.css" | relative_url }}">
<div class = "post-page">
	<div class = "p">
<h3>Motivación</h3>
<br>
Los patrones de diseño son soluciones probadas y documentadas a problemas comunes en el desarrollo de software. 
En la construcción de frameworks de pruebas automatizadas se utilizan para evitar problemas como el alto costo de 
mantenimiento de los tests, código duplicado, entre otros.
<!--more-->
<br><br>
Para la automatización de pruebas contamos con algunos patrones de diseño como: PageObject o ScreenPlay,
pero existen más patrones de diseño que a revisar y probar, con los cuales podríamos refactorizar
nuestros frameworks y hacerlos más robustos.
<br><br>
El concepto de Command Pattern o patron comando lo podemos implementar en muchas situaciones en las que tenemos que 
gestionar tareas que reciben algún tipo de objeto como parámetro y una vez recibido este objeto deberemos procesarle.
<br><br>
Lo que debemos comprender es el hecho de que una solicitud se encapsula en un objeto como comando y se pasa al objeto 
invocador. El objeto invocador busca el objeto apropiado que puede manejar este comando y pasa el comando al objeto 
correspondiente que ejecuta el comando.
<br><br>

<a href="https://github.com/isortegahlabs/poc-Command-Pattern">Repositorio</a>
<br><br>

<h3>Ejercicios</h3>
Como resultado en mi busqueda por la red, me encontre diferentes ejemplos, seleccione los siguientes:
<br><br>

<ul class="list">
<li>
<a href="https://github.com/isortegahlabs/poc-Command-Pattern/tree/develop/src/main/scala/me/isortegah/labs/gestorTareas/Principal.java">Gestor de Tareas</a>      
</li>
<li>
<a href="https://github.com/isortegahlabs/poc-Command-Pattern/tree/develop/src/main/java/me/isortegah/labs/gestorOrdenes/CommandPatternDemo.java">Gestor de Ordenes</a> 
</li>
<li>
<a href="https://github.com/isortegahlabs/poc-Command-Pattern/tree/develop/src/main/java/me/isortegah/labs/gestorEditor/Demo.java">Editor</a> 
</li>
</ul>

<h4>Documentación de Referencia</h4>

<ul class="list">
<li>
<a href="https://www.arquitecturajava.com/command-pattern-tareas/">Command Pattern en Java y la gestion de tareas</a> 
</li>
<li>
<a href="https://www.tutorialspoint.com/design_pattern/command_pattern.htm">Design Patterns - Command Pattern</a>  
</li><li>
<a href="https://refactoring.guru/design-patterns/command">Command</a>
</li><li>
<a href="https://sourcemaking.com/design_patterns/command">Command Design Pattern</a>
</li><li>
<a href="https://www.geeksforgeeks.org/command-pattern/">Command Pattern</a>
</li><li>
<a href="https://medium.com/better-programming/the-command-design-pattern-2313909122b5">The Command Design Pattern</a>
</li><li>
<a href="https://www.dofactory.com/net/command-design-pattern">Command .NET</a>
</li>
<li>
<a href="https://www.journaldev.com/1624/command-design-pattern">Command Design Pattern</a>
</li>
<li>
<a href="https://javarevisited.blogspot.com/2016/05/command-design-pattern-in-java-example-code.html">How to implement Command Design Pattern in Java with Example</a>
</li>
</ul>
    </div>

<br>
</div>
<br>
[Siguiente]({{ page.next.url }})