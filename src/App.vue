<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';

  export default {
    name: 'App',
    components: {
      AppTitle,
      AppHero
    }

  }
</script>
<template>
  <AppTitle/>
  <AppHero/>
</template>


<style>

</style>