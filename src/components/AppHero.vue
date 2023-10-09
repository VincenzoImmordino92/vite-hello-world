
<script>
export default {
  name:'AppHero',
  data(){
    return{
      immagine:'./src/assets/img/Jak&Daxter.jpg'
    }
  }
}
</script>

<template>
  <div class="img">
    <img :src="immagine" alt="">
    <h2>JAK & DAXTER</h2>
    <p>SPACCA</p>
  </div>
</template>

<style scope>

.img{
  text-align: center;
}

img{
  object-fit: contain;
  width: 500px;
  height: 300px;
}
</style>