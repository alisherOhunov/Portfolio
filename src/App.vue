<template>
  <div id="app"> 
    <div id="colorlib-page">
      <div class="container-wrap">
        <SideBar/>
        <div id="colorlib-main">
          <AboutMe/>
          <Service/>
          <Skills/>
          <Education/>
          <Experience/>
          <Blog/>
          <Contact/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SideBar from './components/SideBar.vue';
import AboutMe from './components/AboutMe.vue';
import Service from './components/Service.vue';
import Skills from './components/Skills.vue';
import Education from './components/Education.vue';
import Experience from './components/Experience.vue';
import Blog from './components/Blog.vue';
import Contact from './components/Contact.vue';

export default {
  name: 'App',
  components: {
    SideBar,
    AboutMe,
    Service,
    Skills,
    Education,
    Experience,
    Blog,
    Contact
}
}
</script>
