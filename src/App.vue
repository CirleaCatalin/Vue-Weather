<template>
  <div class="container">
    <nav-bar></nav-bar>
    <content-box></content-box>
    <modal></modal>
  </div>
</template>

<script>
import Content from './components/Content.vue'
import Navbar from './components/Navbar.vue'
import Modal from './components/Modal.vue'
export default {
  components: {
    'content-box': Content,
    'nav-bar': Navbar,
    'modal': Modal
  },
  data () {
    return {
      title: "Dinamic title on parent",
    }
  }
}
</script>

<style>
@import './assets/styles/app.css';
</style>
