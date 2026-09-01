<script setup lang="ts">
const comandosVue = [
	{
		nombre: 'npm install -g @vue/cli',
		paraQueSirve: 'instala Vue CLI de forma global para crear y administrar proyectos Vue.',
	},
	{
		nombre: 'vue create "nombre-del-proyecto"',
		paraQueSirve: 'crea un nuevo proyecto de Vue con el nombre indicado.',
	},
	{
		nombre: 'npm install',
		paraQueSirve: 'instala las dependencias definidas en package.json.',
	},
	{
		nombre: 'npm run dev',
		paraQueSirve: 'inicia el servidor de desarrollo para ejecutar la aplicación localmente.',
	},
]
</script>

<template>
	
  <section class="counter-wrapper2">
    <h3 class="header">Crear un proyecto con Vite</h3>

    <p class="instruction">
      Para crear un proyecto con Vite, puedes usar el siguiente comando:
       <strong>npm create vite@latest nombre-del-proyecto</strong>
    </p>

    <p class="instruction">
      Después, navega al directorio del proyecto y ejecuta:
       <strong>cd nombre-del-proyecto</strong>
    </p>

    <p class="instruction">
      Instala las dependencias:
       <strong>npm install</strong>
    </p>

    <p class="instruction">
      Inicia el servidor de desarrollo:
      <strong>npm run dev</strong>
    </p>
  </section>
  <section class="wiki-section">
		<div class="section-card comandos-card">
			<h3>Comandos básicos de Vue y npm</h3>
			<div class="comandos">
				<div v-for="(comando, index) in comandosVue" :key="index" class="comando">
					<strong>{{ comando.nombre }}</strong>
					<span>{{ comando.paraQueSirve }}</span>
				</div>
			</div>
		</div>
    </section>
</template>

<style scoped>
.topic-card {
  background: #f3e8ff;
  border: 1px solid #e4d7f5;
  border-radius: 12px;
  padding: 20px 22px;
}

h3 {
  color: #3d164d;
  margin: 0 0 12px;
  font-size: 1.4rem;
}

ol {
  margin: 0;
  padding-left: 20px;
  color: #5d4c75;
  line-height: 1.8;
}
</style>
