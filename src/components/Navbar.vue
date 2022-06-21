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
header{
  height: 100px;
  border: 1px solid darkolivegreen;
  display: flex;
  margin-bottom: 30px;
  font-size: 1.5em;
  align-items: center;
  justify-content: space-between;
  /* box-shadow: 0 2px 4px 0 rgba(0,0,0,.1) */
}


</style>
