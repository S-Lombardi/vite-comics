<script>
//Esistono queste componenti
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

//Posso utilizzare le componenti
export default {
  components:{
    Header,
    Main,
    Footer
  }
    
}
</script>

<!-- Visualizzo le componenti -->
<template>
  <div>
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<style lang="scss">
@use './styles/generals.scss' as *;
@use './styles/partials/variables' as *;


</style>
