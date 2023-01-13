<template>
  <q-page class="column">
      <div class="flex flex-center col-grow">
        <img
          alt="Quasar logo"
          src="~assets/quasar-logo-vertical.svg"
          style="width: 200px; height: 200px"
        >
      </div>
  
      <div class="row justify-center q-pa-xl">
        <q-btn to="/new-feature-2" style="width: 200px;" size="lg" color="purple" text-color="white" label="New Feature 2" />
      </div>
    </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
