<template>
  <Navbar/>
  <RouterView />
  <Footer/>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router';
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default{
  components: {
    Navbar,
    Footer
  }
}

//Dizendo quais serão os componentes da minha view
</script>

<style>

</style>