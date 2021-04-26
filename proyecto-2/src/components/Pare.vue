<template>
  <div class="pare">
    <Fill msg="Soc el fill"/>
  </div>
</template>

<script>
import Fill from '../components/Fill.vue'

export default {
  name: 'Pare',
   components: {
    Fill
  },
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
