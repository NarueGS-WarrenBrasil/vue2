<template>
  <div>
    <Navbar />
    <banner />
    <destaques />
    <investir />
    <rodape />
    
  </div>
</template>


<script>
  import Navbar from './components/Navbar.vue'
  import banner from './components/banner.vue'
  import destaques from './components/destaques.vue'
  import rodape from './components/rodape.vue'
  import Investir from './components/Investir.vue'
  export default{
    name: "app",
    components: {
      Navbar,
      banner,
      destaques,
      Investir,
      rodape,
    }
  }
    
  
</script>

<style>
 body{
   font-family: 'Warren Display', 'Montserrat', sans-serif;
 }
</style>

