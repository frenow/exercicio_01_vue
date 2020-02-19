<template>
  <div class="header">
    <img src="imagem.jpg" alt="LOGO">
    <div class="menu"  align="right">
    <ul>
        <li><a href="url">Topic 1</a></li>
        <li><a href="url">Topic 2</a></li>
        <li><a href="url">Topic 3</a></li>
        <li><a href="url">Topic 4</a></li>
    </ul>
    <input type="text" id="search" name="search" value="Search">
    </div>
    <h1>{{ msg }}</h1>
    
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1 {
  text-align: center;
}
ul {
    padding:0px;
    margin:0px;
    list-style:none;
}
li { 
    padding: 2px 10px;
    display: inline-block;
}
</style>
