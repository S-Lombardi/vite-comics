<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  components:{
    Header,
    Main,
    Footer
  }
    
}
</script>

<template>
  <div>
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<style>

.container{
  width: 75%;
  margin: 0 auto;
  border: 1px dashed red;
}

.row{
  width: 100%;
  display: flex;
}

li{
  list-style-type: none;
}

a{
  text-decoration: none;
}

</style>
