<template>
  <div id="app">
    <Header msg="TITULO DA PAGINA"/>
    <Menu />
    <SideBar />
    <Article />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'
import SideBar from './components/SideBar.vue'
import Article from './components/Article.vue'

export default {
  name: 'App', 
  components: {
    Header, Menu, SideBar, Article
  }
}
</script>

<style>
#app {
  color: #2c3e50;
  margin-top: 60px;  
}
</style>

//  text-align: center;
