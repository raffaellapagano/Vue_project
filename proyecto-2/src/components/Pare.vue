<template>
  <div class="caja bg-light">
      <h3>Component Pare</h3>
    <ul class="d-flex flex-column align-items-center">
        <li v-for="item in numerosPadre" v-bind:key="item">
        <Fill :numeroItem="item"></Fill>
        </li>
     </ul>
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
            numerosPadre: ["item 1", "item 2","item 3"]
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
.caja{
    border: 5px solid green;
}
</style>
