<script>
import NavBar from './components/NavBar.vue';
import HeaderComp from './components/HeaderComp.vue';
import ConsultatsComp from './components/ConsultatsComp.vue';
import AboutUs from './components/AboutUs.vue';
export default{
  name: 'App',
  components:{
    NavBar,
    HeaderComp,
    ConsultatsComp,
    AboutUs
  }
}
</script>

<template>
  <NavBar/>
  <HeaderComp/>
  <ConsultatsComp/>
  <AboutUs/>
</template>

<style>

</style>
