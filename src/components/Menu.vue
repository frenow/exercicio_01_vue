<template>
  <div class="menu" align="center">
    <ul>
        <li><a href="url">Section 1</a></li>
        <li><a href="url">Section 2</a></li>
        <li><a href="url">Section 3</a></li>
        <li><a href="url">Section 4</a></li>
    </ul>
   </div>
</template>

<script>
export default {
  name: 'Menu',
  props: {
    msg: String
  }
}
</script>

<style scoped>
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
