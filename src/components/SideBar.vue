<template>
  <div class="SideBar" align="right">
    <ul>
        <li><a href="url">Sidebar 1</a></li>
        <li><a href="url">Sidebar 2</a></li>
        <li><a href="url">Sidebar 3</a></li>
        <li><a href="url">Sidebar 4</a></li>
        <li><a href="url">Sidebar 5</a></li>
        <li><a href="url">Sidebar 6</a></li>
        <li><a href="url">Sidebar 7</a></li>
        <li><a href="url">Sidebar 8</a></li>
        <li><a href="url">Sidebar 9</a></li>
        <li><a href="url">Sidebar 10</a></li>
        <li><a href="url">Sidebar 11</a></li>
        <li><a href="url">Sidebar 12</a></li>
        <li><a href="url">Sidebar 13</a></li>
    </ul>
   </div>
</template>

<script>
export default {
  name: 'SideBar',
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
}
</style>
