<script >
//import component h1
import HeaderMenuComponent from './components/HeaderMenuComponent.vue';
import HeaderLogoComponent from './components/HeaderLogoComponent.vue';
import MainComponent from './components/MainComponent.vue';
import MainTopComponent from './components/MainTopComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import FooterTopComponent from './components/FooterTopComponent.vue';



// my-component.js
export default {
  name:"App",
  data() {
    return 
  },
  components:{
    // HEADER
    HeaderMenuComponent,
    HeaderLogoComponent,

    // MAIN
    MainTopComponent,
    MainComponent,

    // FOOTER
    FooterComponent,
    FooterTopComponent,

  }
}
</script>

<template>
    <div class="my-container">
      <HeaderMenuComponent />
      <MainTopComponent/>
      <MainComponent />
      <FooterTopComponent />
      <FooterComponent />
    </div>
</template>

<style scoped>
  
</style>
