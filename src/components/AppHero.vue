<script>
import AppTitle from './AppTitle.vue';
export default {
    name: 'AppHero',
    data() {
        return {

        }
    },
    components: {
        AppTitle
    }

}
</script>

<template>
    <div class="container">
        <AppTitle></AppTitle>
        <span>
            ---- ciao sono il titolo e sono anche dentro il jumbo, questa volta però bianco</span>
        <h2>Sono il tuo jumbotron!</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nisi molestias aliquam reiciendis ad ipsa,
            numquam
            repellat est cumque magnam voluptatum eum modi tempore aspernatur itaque neque facilis, consectetur,
            odio
            tempora!</p>
    </div>
</template>

<style scoped>
.container {
    background: linear-gradient(90deg, rgba(131, 58, 180, 1) 0%, rgba(253, 29, 29, 1) 50%, rgba(252, 176, 69, 1) 100%);
    height: 50vh;
    width: 100vw;
    margin: 20px;
    border-radius: 20px;
    color: white;
    padding: 100px;
}

h2 {
    color: white;
    font-family: Arial, Helvetica, sans-serif;
}
</style>
