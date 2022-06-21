<template>
  <div class="hello">
    <h3>Create something cool in {{msg}}</h3>
    <h5>Name: {{name}}</h5>
    <h5>Height: {{height}}</h5>
    <h5>Weight: {{weight}}</h5>
    <h5>Type: {{types}}</h5>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return{
      name:"",
      height:"",
      weight:"",
      types:""
    }

  },
  mounted(){
    //implement with fetch and promises a call to pokeapi
    //usage: join the base url with your query (ie: https://pokeapi.co/api/v2/pokemon/bulbasaur)
    // eslint-disable-next-line
    const BASE_API_URL='https://pokeapi.co/api/v2/pokemon/'
  
    this.name="Bulbasaur"
    this.height="7"
    this.weight="69"
    this.types="grass and poison"
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
