<template>
  <div class="border border-success m-3 p-3 bg-white caja">
     <h4>{{numeroItem}}</h4>
     <button class="btn btn-success" @click="numero++">{{numero}}</button>
  </div>
</template>

<script>
export default {
  name: 'Fill',
  props:["numeroItem"],
  data(){
        return{ 
            numero: 0
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
    width: 300px;
}
</style>
