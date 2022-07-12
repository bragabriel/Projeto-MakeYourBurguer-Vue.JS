<template>
  <Navbar :logo="logo_src" :alt="app_name" />
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
  },
  data(){
    return{
      logo_src: "/img/logo.png",
      app_name: "Make Your Burguer"
    }
  }
}

//Dizendo quais serão os componentes da minha view
</script>

<style>
  *{
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  html{
    min-height: 1080px;
  }

  .main-container{
    margin:50px;
    min-height: 250px;
  }

  body{
    display: flex;
    flex-direction: column;
  }

  h1{
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color:#222;
  }
</style>