<script >
//import component h1
import HeaderMenuComponent from './components/HeaderMenuComponent.vue';
import MainComponent from './components/MainComponent.vue';
import MainTopComponent from './components/MainTopComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import FooterTopComponent from './components/FooterTopComponent.vue';
import cardComponent from './components/cardComponent.vue';



// my-component.js
export default {
  name:"App",
  data() {
    return {
      
    }
  },
  components:{
    // HEADER
    HeaderMenuComponent,
    

    // MAIN
    MainTopComponent,
    MainComponent,

    // FOOTER
    FooterComponent,
    FooterTopComponent,

    //CARD-ELEMENT
    cardComponent,
  }
}
</script>

<template>
    <div class="container-fluid ">
      <div class="header-color-bg">
        <header  class="my-container">

          <HeaderMenuComponent />

        </header>
      </div>
      <div class="header-bottom-bgc">

        <div class="my-container">
          <MainTopComponent />
        </div>

      </div>
      

      <main class="bgc">
        <div class="my-container">
          <MainComponent />
        </div>
        

      </main>
      <section class="bg-main-content">
        <footer class="my-container">
          <FooterTopComponent />
          
        </footer>
      </section>

      <section class="footer-bottom-bgc">
        <div class="my-container">
          <FooterComponent />
        </div>
      </section>
    </div>
    <div>
    <div class="my-container">
    <cardComponent/>
    </div>
  </div>  
</template>

<style scoped>
@import "../src/assets/scss/partials/reset.scss";

  .my-container{
    max-width: 70%;
    margin: 0 auto;
    
  }
  .header-color-bg{
    background-color: white;
  }
  .header-bottom-bgc{
    background-color: rgb(28, 28, 28);
  }
  .bgc{
    background-color: rgb(2, 130, 249);
  }
  .footer-bottom-bgc{
    background-color: rgb(48, 48, 48);
  }

  .bg-main-content{
        background-image: url(./assets/img/footer-bg.jpg);
        background-size: calc(100vw);
        background-position:center;
        background-repeat: no-repeat;
        
    }
</style>
