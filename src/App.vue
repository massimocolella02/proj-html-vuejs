<script>
import NavBar from './components/NavBar.vue';
import HeaderComp from './components/HeaderComp.vue';
import ConsultatsComp from './components/ConsultatsComp.vue';
import AboutUs from './components/AboutUs.vue';
import ProjectCom from './components/ProjectCom.vue'

export default{
  name: 'App',
  components:{
    NavBar,
    HeaderComp,
    ConsultatsComp,
    AboutUs,
    ProjectCom
  }
}
</script>

<template>
  <NavBar/>
  <HeaderComp/>
  <ConsultatsComp/>
  <AboutUs/>
  <ProjectCom/>
</template>

<style>

</style>
