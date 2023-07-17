<script>
// my-component.js
export default {
    data() {
        return 
    },
}
</script>

<template>
    <div class="footer-content d-flex justify-content-between align-items-center py-4">
      <div>
        <button type="button" class="btn btn-outline-secondary text-light fw-bolder">SIGN-UP NOW!</button>
      </div>
      <div class="social-icons d-flex">
        <h4 class="fw-bold align-content-baseline">FOLLOW US</h4>
        <img src="../assets/img/footer-facebook.png" alt="Facebook" @click="handleClick('facebook')">
        <img src="../assets/img/footer-twitter.png" alt="Twitter" @click="handleClick('twitter')">
        <img src="../assets/img/footer-periscope.png" alt="periscope" @click="handleClick('periscope')">
        <img src="../assets/img/footer-pinterest.png" alt="LinkedIn" @click="handleClick('pinterest')">
        <img src="../assets/img/footer-youtube.png" alt="YouTube" @click="handleClick('youtube')">
      </div>
    </div>
  </template>
  

<style lang="scss" scoped>
  button{
    border:1px solid rgb(6, 124, 233);
    border-radius: 0;
  }
 
  .social-icons> *{
    margin: 10px;
    height: 30px;
  }
  h4 {
    color: rgb(9, 129, 249);
  }
  .footer-content{
    position: relative;
        
  }
</style>