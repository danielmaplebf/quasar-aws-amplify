<template>
    <q-page class="column justify-between text-center">
      <h2>New Feature 1</h2>

      <div class="q-mb-xl">
        <q-btn to="/" style="width: 150px;" size="lg" color="orange" text-color="white" label="Home" />
      </div>
    </q-page>
  </template>
  
  <script>
  import { defineComponent } from 'vue'
  
  export default defineComponent({
    name: 'NewFeature1Page'
  })
  </script>
