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
    position:relative;
    float: left;
    border-style: solid;
    width: 300px;
    height: 200px;    
}
.texto {
    border:1px solid;
    height: 210px;
    text-align: left;
    margin-top: 30px;
    margin-bottom: 10px;
    padding-top: 10px;
    padding-left: 5px;
    width: 500px;
}
div{
    margin-right: auto;
    margin-left: auto;
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
