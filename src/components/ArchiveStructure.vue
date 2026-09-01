<script setup lang="ts"></script>

<template>
  <section class="topic-card">
    <h3>4. Estructura de carpetas o archivos</h3>
    <div class="lista-carpetas">
      <p><strong>Carpeta</strong>: <strong>Función</strong></p>
      <p><strong>src</strong>: Código principal</p>
      <p><strong>assets</strong>: Imágenes y estilos</p>
      <p><strong>components</strong>: Componentes reutilizables</p>
      <p><strong>public</strong>: Archivos públicos</p>
      <p><strong>App.vue</strong>: Componente principal</p>
    </div>
  </section>
</template>

<style scoped>
.topic-card {
  background: #f0f7ff;
  border: 1px solid #dfeeff;
  border-radius: 12px;
  padding: 20px 22px;
}

h3 {
  color: #3d164d;
  margin: 0 0 12px;
  font-size: 1.4rem;
}

.lista-carpetas {
  display: grid;
  gap: 8px;
}

p {
  margin: 0;
  color: #3d164d;
  line-height: 1.7;
}
</style>
