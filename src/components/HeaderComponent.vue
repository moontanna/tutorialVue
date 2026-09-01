<script setup lang="ts"></script>
<template>
	<header class="hero-header">
		<div class="hero-content">
			<h1>¿Framework con vite?</h1>
			<h2>Vite es una herramienta rápida para desarrollar aplicaciones web modernas.</h2>
			<p>Usa HTML, CSS y TypeScript para crear aplicaciones web modernas y rápidas.</p>

			<div class="info-block">
				<p class="info-label">Necesitarás:</p>
				<ul>
					<li>Node.js</li>
					<li>npm</li>
					<li>Visual Studio Code</li>
					<li>Navegador web</li>
				</ul>

				<p class="info-label">Antes de aprender a programar en Vue es conveniente conocer:</p>
				<ul>
					<li>HTML</li>
					<li>CSS</li>
					<li>JavaScript básico</li>
					<li>Manejo de archivos y carpetas</li>
				</ul>
			</div>
		</div>
	</header>
</template>

<style scoped>
.hero-header {
	position: relative;
	background: #5d2a6d;
	padding: 36px 28px;
	border-radius: 22px;
	border: none;
	box-shadow: none;
	overflow: hidden;
}

.hero-content {
	position: relative;
	z-index: 1;
	display: grid;
	gap: 12px;
	max-width: 780px;
	margin: 0 auto;
	text-align: center;
}

h1,
h2,
p {
	margin: 0;
	color: #ffffff;
}

h1 {
	font-size: clamp(2rem, 3vw, 3.2rem);
	line-height: 1.1;
	letter-spacing: -0.04em;
}

h2 {
	font-size: clamp(1.1rem, 2vw, 1.6rem);
	font-weight: 500;
	line-height: 1.5;
	color: rgba(255, 255, 255, 0.9);
}

p {
	font-size: 1rem;
	line-height: 1.7;
	color: rgba(255, 255, 255, 0.88);
}

.info-block {
	margin-top: 8px;
	text-align: left;
	background: rgba(255, 255, 255, 0.08);
	border: 1px solid rgba(255, 255, 255, 0.12);
	border-radius: 14px;
	padding: 18px 20px;
}

.info-label {
	font-weight: 700;
	margin-bottom: 8px;
	color: #ffffff;
}

ul {
	margin: 0 0 16px;
	padding-left: 20px;
	color: rgba(255, 255, 255, 0.9);
	line-height: 1.8;
}

ul:last-child {
	margin-bottom: 0;
}
</style>
