<script>
import NavBar from './components/NavBar.vue';
import HeaderComp from './components/HeaderComp.vue';
import ConsultatsComp from './components/ConsultatsComp.vue';
import AboutUs from './components/AboutUs.vue';
import ProjectCom from './components/ProjectCom.vue'
import TestimonialComp from './components/TestimonialComp.vue'
import BlogComp from './components/BlogComp.vue';

export default{
  name: 'App',
  components:{
    NavBar,
    HeaderComp,
    ConsultatsComp,
    AboutUs,
    ProjectCom,
    TestimonialComp,
    BlogComp
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
  <BlogComp/>
</template>

<style>

</style>
