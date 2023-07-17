<script>
// my-component.js

export default {
    data() {
        return {
            cards: [
            {
                imgSrc: "/src/assets/img/buy-comics-digital-comics.png",
                altText: "DIGITAL COMICS",
                title: "DIGITAL COMICS",
            },
            {
                imgSrc: "/src/assets/img/buy-comics-merchandise.png",
                altText: "DC MERCHANDISE",
                title: "DC MERCHANDISE",
            },
            {
                imgSrc: "/src/assets/img/buy-comics-subscriptions.png",
                altText: "SUBSCRIPTION",
                title: "SUBSCRIPTION",
            },
            {
                imgSrc: "/src/assets/img/buy-comics-shop-locator.png",
                altText: "COMIC CHOP LOCATOR",
                title: "COMIC CHOP LOCATOR",
            },
            {
                imgSrc: "/src/assets/img/buy-dc-power-visa.svg",
                altText: "DC POWER VISA",
                title: "DC POWER VISA",
            },
            ],
        };
    },
};
</script>

<template>
    <div class="my-cardContainer">
        <div v-for="(card, index) in cards" :key="index" class="card">
            <div class="card-content d-flex p-3">
                <i><img :src="card.imgSrc" :alt="card.altText"></i>
                <p>{{ card.title }}</p>
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

i > img {
    height: 50px;
}

.card-content p {
    line-height: 1;
    font-size: 10px;
}

.card {
    border-radius: 0%;
    flex: 1 0 20%; /* Imposta la larghezza del 20% */
    display: flex;
    justify-content: center;
    align-items: center;
    border: none;
    background-color: transparent;
    color: white;
}

</style>