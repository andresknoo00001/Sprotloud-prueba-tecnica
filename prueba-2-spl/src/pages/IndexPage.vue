<template>
  <q-page class="flex flex-center">

    <prueba/>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import prueba from "components/PruebaTecnica.vue";
export default defineComponent({
  components:{
    prueba
  },
  name: 'IndexPage'
})
</script>
