<script>
import NavBar from './components/NavBar.vue';
import HeaderComp from './components/HeaderComp.vue';
import ConsultatsComp from './components/ConsultatsComp.vue';
import AboutUs from './components/AboutUs.vue';
import ProjectCom from './components/ProjectCom.vue'
import TestimonialComp from './components/TestimonialComp.vue'

export default{
  name: 'App',
  components:{
    NavBar,
    HeaderComp,
    ConsultatsComp,
    AboutUs,
    ProjectCom,
    TestimonialComp
  }
}
</script>

<template>
  <NavBar/>
  <HeaderComp/>
  <ConsultatsComp/>
  <AboutUs/>
  <ProjectCom/>
  <TestimonialComp/>
</template>

<style>

</style>
