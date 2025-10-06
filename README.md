# Artistas_ejs
codigo con js y ejs de artistas
<%- include("templates/header.ejs") %>
	<h1 class="text-primary">Este es el apartado de Contactanos</h1>
	<link rel="stylesheet" href="estilo.css">
    <p>
        Este apartado esta hecho paraq que puedas contactarnos mediante distintos medios.
    </p>

    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi ad praesentium nihil accusamus, adipisci illum itaque ipsa! Impedit repudiandae sed fuga architecto assumenda dolore, recusandae enim debitis! Aliquam, deleniti tempora?</p>

    <a href="www.instagram.com" class="instagram">Nuestro Instagram</a>
    <include 
<form action="/contactanos" method="POST" class="form-contacto">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" required>

  <label for="edad">Edad:</label>
  <input type="number" id="edad" name="edad" min="1" required>

  <button type="submit">Enviar</button>
</form>
