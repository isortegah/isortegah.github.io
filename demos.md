---
layout: page
title: Demos
permalink: /demos/
---
<link rel="stylesheet" href="{{ "/assets/css/demo.css" | relative_url }}">
<div class = "p head">El objetivo de los POC's que estaré publicando, es el ír compartiendo los frameworks que he venido implementado en mis diferentes trabajos, tales implementaciones me han dejado una serie de conocimientos, los cuales busco relacionar para implementar una plataforma de pruebas que me permita diseñar, crear y ejecutar las mismas con muy pocos pasos, reduciendo el tiempo de la preparación de las pruebas y permitiendo que el tiempo sobrante pueda continuar con el aprendizaje de nuevas tecnologías y mejorar la plataforma.
<br><br>
</div>
{% assign pocs = site.posts |where_exp: 'p',"p.label contains 'poc'"%}
{% for poc in pocs %}
### [{{poc.title}}]({{poc.url}})
<div class = "demo-page">
      {{ poc.excerpt }} 
      <div class="seccMas"><br>
      <a href="{{ poc.url }}" class="more">Más ...</a>
      </div>
      
      <br>
</div>
{% endfor %}
