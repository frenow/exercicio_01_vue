<template>
  <div id="app">
    <Header msg="TITULO DA PAGINA"/>
    <Menu />
    <SideBar />
    <Article v-for="artigo in artigos" :msg="artigo.text" v-bind:key="artigo.text" />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Menu from './components/Menu.vue'
import SideBar from './components/SideBar.vue'
import Article from './components/Article.vue'

export default {
  name: 'App', 
  data() {
    return {
      artigos: [
        {text: "Linha 1 - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ultrices viverra metus non tincidunt. Ut tortor ipsum, fringilla in ex vitae, malesuada euismod urna. Donec diam sapien, laoreet in vulputate non, feugiat sed mi. Etiam feugiat non nulla sed tincidunt. Duis vehicula magna viverra mauris porttitor, et finibus mauris aliquam."},
        {text: "Linha 2 - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ultrices viverra metus non tincidunt. Ut tortor ipsum, fringilla in ex vitae, malesuada euismod urna. Donec diam sapien, laoreet in vulputate non, feugiat sed mi. Etiam feugiat non nulla sed tincidunt. Duis vehicula magna viverra mauris porttitor, et finibus mauris aliquam."},
        {text: "Linha 3 - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ultrices viverra metus non tincidunt. Ut tortor ipsum, fringilla in ex vitae, malesuada euismod urna. Donec diam sapien, laoreet in vulputate non, feugiat sed mi. Etiam feugiat non nulla sed tincidunt. Duis vehicula magna viverra mauris porttitor, et finibus mauris aliquam."}
      ]
    };
  },
  components: {
    Header, Menu, SideBar, Article
  }
};
</script>

<style>
#app {
  color: #2c3e50;
  margin-top: 60px;  
}
</style>

//  text-align: center;
