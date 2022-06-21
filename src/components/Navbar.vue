<template>
 <header class="header">
   <h1 id="title">Weather App</h1>
   <control-panel></control-panel>
 </header>
</template>

<script>
import Control from './Control.vue'
  export default {
  components:{
    'control-panel': Control
  },
  data () {
    return {
    }
  }

}
</script>

<style>
@import '../assets/styles/navbar.css';
</style>
