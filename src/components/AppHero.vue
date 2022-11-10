<script>
export default {
    jumbo: "AppHero",
    data() {
        return { 
            img: "Vite-Vue.png"
        } 

    },
}
</script>
<template>
    <img :src="`../img/${img}`" alt="">
</template>

<style>
img {
    width:60%;
}
.container {
    width: 80%;
    text-align: center;
    margin:auto;
}
</style>