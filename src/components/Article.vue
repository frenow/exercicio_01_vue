<template>
  <div class="article" align="center">
    <div class="image">
        <img src="imagem.jpg" alt="IMG" >
    </div>
    <div class="texto">
        <p>{{ msg }}
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
