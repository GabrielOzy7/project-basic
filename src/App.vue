<script  lang="ts">
import {defineComponent} from 'vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap.js"
import Grid from './components/Grid.vue'
export default defineComponent({
  name :'App',
  components :{
    Grid
  }
})



</script>

<template>
 <Grid/>
  
</template>

