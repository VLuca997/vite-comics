<script>
// my-component.js
export default {
    data() {
    return 
    },
}
</script>

<template>
    <div class="my-boxContainer">
        <div class="box">
            <div class="box-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
        <div class="box">
            <div class="box-content d-flex p-3 justify-content-baseline">
            <i>Icona</i>
            <p>Contenuto</p>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
    
    .my-boxContainer {
    display: flex;
    width: 80vw;
    height: 9.375rem;
}

.box {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid black;
}

</style>