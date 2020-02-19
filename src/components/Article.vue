<template>
  <div class="article" align="center">
    <div class="image">
        <img src="imagem.jpg" alt="IMG" >
    </div>
    <div class="texto">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ultrices viverra metus non tincidunt. 
            Ut tortor ipsum, fringilla in ex vitae, malesuada euismod urna. Donec diam sapien, 
            laoreet in vulputate non, feugiat sed mi. Etiam feugiat non nulla sed tincidunt. 
            Duis vehicula magna viverra mauris porttitor, et finibus mauris aliquam.
        </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Article',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.image {
    border-style: solid;
    width: 300px;
    height: 200px;    
}
.texto {
    border-style: solid;
    width: 300px;
    height: 200px;
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
