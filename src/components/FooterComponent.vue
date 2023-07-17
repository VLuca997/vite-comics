<script>
// my-component.js
export default {
    data() {
        return 
    },
}
</script>

<template>
    <div class="footer-content d-flex justify-content-between align-items-center">
      <div>
        <button type="button" class="btn btn-outline-secondary">PRESS</button>
      </div>
      <div class="social-icons">
        <img src="../assets/img/footer-facebook.png" alt="Facebook" @click="handleClick('facebook')">
        <img src="../assets/img/footer-twitter.png" alt="Twitter" @click="handleClick('twitter')">
        <img src="../assets/img/footer-periscope.png" alt="periscope" @click="handleClick('instagram')">
        <img src="../assets/img/footer-pinterest.png" alt="LinkedIn" @click="handleClick('linkedin')">
        <img src="../assets/img/footer-youtube.png" alt="YouTube" @click="handleClick('youtube')">
      </div>
    </div>
  </template>
  

<style lang="scss" scoped>
h3{
    text-align: center;
    color: red;
}

</style>