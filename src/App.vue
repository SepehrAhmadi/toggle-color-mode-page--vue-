<template>
<section class="site-container">
    <Header :darkMode="darkMode" :toggleDarkMode="toggle" />
    <MainContent :darkMode="darkMode" />
    <Footer :darkMode="darkMode" />
</section>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import MainContent from './components/MainContent.vue'

export default {
    name: "App",
    components: {
        Header,
        Footer,
        MainContent
    },
    data() {
        return {
            darkMode: false
        }
    },
    methods: {
        toggle() {
            this.darkMode = !this.darkMode
        }
    }
}
</script>

<style scoped>
/* .site-container {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
} */
</style>
