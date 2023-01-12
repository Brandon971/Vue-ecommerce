<template >
  <navbarVue></navbarVue> 
  <router-view></router-view>
  <footerVue></footerVue>
</template>
<script>
import navbarVue from './components/navbar.vue';
import footerVue from './components/footer.vue';


export default {
  components :{
    navbarVue,
    footerVue
  }
  
}
</script>
<style>
</style>