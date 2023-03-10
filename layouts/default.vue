<template>
  
  <div>
    <main>
      <slot></slot>
    </main>
  </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue'
import { initModals } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
  initModals();
})
</script>