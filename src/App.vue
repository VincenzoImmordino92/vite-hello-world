<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  name:'App',
  components:{
    AppTitle,
    AppHero,
},
  data(){
    return{
      titolo:'HELLO WORLD'
    }
  }
}
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style>

</style>