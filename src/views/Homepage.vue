<template>
    <section>
        <h1>Thanks for attending our wedding.</h1>
        <p>Please click on the button below to donate.</p>
        <router-link to="/donate-page"><button>Donate</button></router-link>
    </section>
</template>

<script>
export default {
    name: "Homepage",
    data() {
        return {

        }
    }
}
</script>

<style scoped>
h1 {
    font-size: 40px;
    color: tomato;
}
button {
    width: 200px;
    height: 50px;
    border-radius: 5px;
}
</style>