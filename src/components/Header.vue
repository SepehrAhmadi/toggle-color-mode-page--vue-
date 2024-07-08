<template>
<nav :class="{ nav: true, dark: this.darkMode }">
    <img class="nav-logo-icon" src='../assets/logo.svg' />
    <h3 class="nav-logo-text">Vue Facts</h3>

    <div class="toggler">
        <p class="toggler-light">Light</p>
        <div class="toggler-slider" v-on:click="toggleDarkMode">
            <div class="toggler-slider-circle"></div>
        </div>
        <p class="toggler-dark">Dark</p>
    </div>
</nav>
</template>

<script>
export default {
    name: "Header",
    props: {
        darkMode: Boolean,
        toggleDarkMode: Function,
    }
}
</script>

<style scoped >

</style>
