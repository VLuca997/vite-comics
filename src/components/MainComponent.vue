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
            <div class="card-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
    
    .my-cardContainer {
    display: flex;
    
    height: 9.375rem;
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