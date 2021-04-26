<template>
  <div class="bg-danger m-auto" style="width: 200px">
     <h4>Item {{numeroItem}}</h4>
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
</style>
