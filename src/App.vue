<script>
import NavBar from './components/NavBar.vue';
import HeaderComp from './components/HeaderComp.vue';
import ConsultatsComp from './components/ConsultatsComp.vue';
export default{
  name: 'App',
  components:{
    NavBar,
    HeaderComp,
    ConsultatsComp
  }
}
</script>

<template>
  <NavBar/>
  <HeaderComp/>
  <ConsultatsComp/>
</template>

<style>

</style>
