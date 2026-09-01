<script setup lang="ts">
import HeaderComponent from './components/HeaderComponent.vue'
import WhatIsFramework from './components/WhatIsFramework.vue'
import VueRequirements from './components/VueRequirements.vue'
import CreateAproject from './components/CreateAproject.vue'
import ArchiveStructure from './components/ArchiveStructure.vue'
import WhatIsComponent from './components/WhatIsComponent.vue'

</script>

<template>
  <div class="page-shell">
    <HeaderComponent />
    <WhatIsFramework />
    <VueRequirements />
    <CreateAproject />
    <ArchiveStructure />
    <WhatIsComponent />
  
  </div>
</template>

<style scoped>
.page-shell {
  display: grid;
  gap: 20px;
  padding: 20px;
  background: #f7f2fa;
}
</style>
