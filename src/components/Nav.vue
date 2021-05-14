<template>
  <div class="NavBar">
<ul>
  <li class="nav"><a href="#">Home</a></li>
  <li class="nav"><a href="#">About</a></li>
  <li class="nav"><a href="#">b</a></li>
  <li class="nav"><a href="#">c</a></li>
  <li class="nav"><a href="#">d`</a></li>
  </ul>   
  </div>
</template>

<script>
export default {
  name: 'Amit',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  display:flex;
  flex-grow: 1;
  padding: 1em 1em 1em 1em;
  width:100%;
}
li {
  display: inline-block;
  width:100%;
  gap:1em;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
