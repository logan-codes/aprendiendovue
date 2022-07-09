<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>{{ mensaje }}</p>
   
  </div>
</template>

<script>
export default {
  data: () => ({
    info: 2 * 2 //En la data se declaran las viariables reactivas. Para acceder
                //a una variable se usa this. 
  }),
  name: 'HelloWorld',
  props: {
    msg: String,
    mensaje: String
  },
  beforeCreate(){
    console.log("Hook before create")
  },
  created(){
    console.log("Hook created")
    this.info = console.log(this.info)
  },
  mounted(){
    console.log("Hook mounted")
    console.log(this.$el.querySelectorAll('p'));
  }
}
</script>


<style scoped>

</style>
