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
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

:root {
  --fontcolor: #313131;
  --bgcolor: #FAFAFA;
}
html {
  font-family: "Roboto", sans-serif;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  background-color: var(--bgcolor);
  margin: 0;
  color: var(--fontcolor);
  transition: background-color 500ms cubic-bezier(0.075, 0.82, 0.165, 1);
}
.container {
  max-width: 85vw;
  margin: 0 auto;
}

</style>
