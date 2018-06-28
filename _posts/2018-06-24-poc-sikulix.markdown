---
layout: post
title:  "POC Sikulix"
date:   2018-06-28 11:59:12 -0500
categories: sikulix update
permalink: /pocs/poc-sikulix.html
---
<link rel="stylesheet" href="{{ "/assets/css/post.css" | relative_url }}">
<div class = "post-page">
	<div class = "p">
<a href="http://sikulix.com">Sikulix</a> es una herramienta que nos permite automatizar la ejecución de acciones (click, tipeado, ejecución de programas, drag and drop) sobre todo lo que vemos en la pantalla de la computadora. Es de gran ayuda cuando no tenemos acceso al DOM de la página Web o si queremos automatizar tareas sobre aplicaciones que no proporcionan otra interfaz que permita la ejecución automática de tareas sobre ellas. En su <a href="http://sikulix.com">Sitio Oficial</a> podrán encontra mas información acerca de sus características.
    </div>
    
<br> 
<div class = "p">Para la automatización de pruebas es de bastante utilidad esta herrameinta, y la podemos combinar con Selenium, esto cuando queremos validar por ejemplo que la posición en la pantalla de algun elemento no haya cambiado, realizar pruebas de regresión sobre el responsive de nuestra página. En mi experiencia personal se presento el caso de que se servia una plataforma a través de una herramienta de Symantec llamada <a href="https://www.symantec.com/products/web-isolation">"Fireglass"</a>, la cual oculta el DOM de la página, por lo que Selenium dejo de ser una opción para automatizar las pruebas que requeria realizar.</div>
<br>
<div class = "p">
    En el repo <a href="https://github.com/isortegah/poc_sikulix" target="_blank">poc_sikulix</a> que se encuentra en Github, realice una pequeña prueba de concepto, que muestra la ejecución de una simple prueba con sikulix pero implementando TestNG en conjunto con Cucumber y su ejecución será lanzada a través de MAVEN.
    <br><br>
    Cualquier aportación es bienvenida y espero su feedback en cualquiera de mis redes sociales.
</div>

</div>