<script>
// my-component.js
export default {
    data() {
    return 
    },
}
</script>

<template>
    <div class="my-cardContainer">
        <div class="card">
            <div class="card-content d-flex p-3">
            <i><img src="../assets/img/buy-comics-digital-comics.png" alt=""></i>
            <p>DIGITAL COMICS</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3">
            <i><img src="../assets/img/buy-comics-merchandise.png" alt=""></i>
            <p>DC MERCHANDISE</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3">
            <i><img src="../assets/img/buy-comics-subscriptions.png" alt=""></i>
            <p>SUBSCRIPTION</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3">
            <i><img src="../assets/img/buy-comics-shop-locator.png" alt=""></i>
            <p>COMIC CHOP LOCATOR</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3">
            <i><img src="../assets/img/buy-dc-power-visa.svg" alt=""></i>
            <p>DC POWER VISA</p>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
    
    .my-cardContainer {
    display: flex;
    
    height: 9.375rem;
}
.card-content {
        display: flex;
        align-items: center;
    }
    
    .card-content i {
        margin-right: 10px;
    }
    i > img{
        height: 50px;
    }
    i:nth-child(5){
        height: 1000px;
    }
    
    .card-content p {
        line-height: 1;
        font-size: 10px;
    }

.card {
    border-radius: 0%;
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    border: none;
    background-color: transparent;
    color: white;
}

</style>