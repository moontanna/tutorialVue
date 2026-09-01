<script setup lang="ts"></script>

<template>
  <section class="topic-card">
    <h3>5. ¿Qué es y para qué sirve un componente?</h3>
    <p>
      Un componente es una pieza reutilizable de la interfaz, como un botón, un menú o una tarjeta.
      Permite dividir la aplicación en partes pequeñas y organizadas, facilitando el mantenimiento y
      la reutilización del código.
    </p>
  </section>
  <div class="section-card conceptos-card">
			<h3>Conceptos clave</h3>
			<div class="conceptos">
				<p><strong>Template:</strong> define la estructura HTML que se muestra en pantalla y organiza el contenido del componente.</p>
				<p><strong>Script:</strong> contiene la lógica, los datos y las funciones que hacen que el componente sea interactivo.</p>
				<p><strong>Style:</strong> contiene los estilos CSS que determinan la apariencia, los colores y el diseño del componente.</p>
			</div>
		</div>

		<div class="section-card etiquetas-card">
			<h3>Etiquetas HTML útiles</h3>
			<ul>
				<li>Títulos: &lt;h1&gt;, &lt;h2&gt;, &lt;h3&gt;, &lt;h4&gt;, &lt;h5&gt; y &lt;h6&gt;.</li>
				<li>Párrafos: &lt;p&gt;.</li>
				<li>Imágenes: &lt;img&gt;.</li>
			</ul>
		</div>
	
</template>

<style scoped>
.topic-card {
  background: #f9f3eb;
  border: 1px solid #f0e1c6;
  border-radius: 12px;
  padding: 20px 22px;
}

h3 {
  color: #3d164d;
  margin: 0 0 12px;
  font-size: 1.4rem;
}

p {
  color: #5d4c75;
  line-height: 1.7;
  margin: 0;
}
</style>
