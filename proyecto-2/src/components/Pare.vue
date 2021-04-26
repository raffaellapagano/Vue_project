<template>
  <div class="bg-primary">
    <Fill :numeroItem="numeroPadre"></Fill>
  </div>
</template>

<script>
import Fill from '../components/Fill.vue'

export default {
  name: 'Pare',
   components: {
    Fill
  },
  data(){
        return{
            numeroPadre: 1
        }
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
