<template>
  <div>
  <h1>{{ titulo}}</h1>
  <img class="img-responsive" :src="foto.url" :alt="foto.titulo" />
  </div>
</template>

<script>
export default {
  data(){
    return{
      titulo:"Alura Pic",
      foto:{
        url:"https://abrilsuperinteressante.files.wordpress.com/2016/03/cachorro.png",
        titulo:"cachorro"
      }
    }
  }
 
}
</script>

<style>
  img{
    width: 10em
  }
</style>
