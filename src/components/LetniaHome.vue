<template>
  <div class="container">
    <h3>Letnia kolonia</h3>
    <button class="btn mr-2 mb-2 btn-primary" type="button">
        <span class="btn-text">Primary</span>
    </button>
  </div>
</template>

<script>
export default {
  name: 'LetniaHome',
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
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
