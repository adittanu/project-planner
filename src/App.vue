<template>
    <Navbar />
    <RouterView />
</template>

<script>
import Navbar from "./components/Navbar.vue"

export default {
    components: { Navbar },
}
</script>

<style>
body {
    background: #f2f2f2;
}
#app {
    font-family: Arial, Helvetica, sans-serif;
    -webkit-font-smoothing: antialiases;
    -moz-osx-font-smoothing: grayscale;
    max-width: 600px;
    margin: 0 auto;
    color: #555;
}
</style>
