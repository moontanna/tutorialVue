<script setup lang="ts">
import HeaderComponent from './components/HeaderComponent.vue'
import WhatIsFramework from './components/WhatIsFramework.vue'
import VueRequirements from './components/VueRequirements.vue'
import CreateAproject from './components/CreateAproject.vue'
import ArchiveStructure from './components/ArchiveStructure.vue'
import WhatIsComponent from './components/WhatIsComponent.vue'
import componente from './components/componente.jpg'
import rkive from './components/rkive.png'
</script>

<template>
  <div class="pagina">
    <HeaderComponent />
    <WhatIsFramework />
    <VueRequirements />
    <CreateAproject />
    <ArchiveStructure />

    <div class="image-row">
      <div class="image-card">
        <img :src="rkive" alt="Imagen de estructura de carpetas" class="wiki-image" />
        <p>Estructura básica de un proyecto Vue con carpetas y archivos principales.</p>
      </div>

      
    <WhatIsComponent />
      <div class="image-card">
        <img :src="componente" alt="Imagen de componente" class="wiki-image" />
        <p>Ejemplo visual de un componente reutilizable dentro de una interfaz.</p>
      </div>
    </div>

  </div>
</template>

<style scoped>
.pagina {
  display: grid;
  gap: 20px;
  padding: 20px;
  background: #f7f2fa;
}

.image-row {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
}

.image-card {
  background: #f7f0ff;
  border: 1px solid #e4d7f5;
  border-radius: 12px;
  padding: 16px;
  max-width: 420px;
  width: 100%;
  box-shadow: 0 8px 20px rgba(61, 22, 77, 0.05);
}

.wiki-image {
  width: 100%;
  display: block;
  border-radius: 12px;
  border: 1px solid #e4d7f5;
  margin-bottom: 12px;
}

.image-card p {
  margin: 0;
  color: #3d164d;
  line-height: 1.6;
  font-size: 0.95rem;
}
</style>
