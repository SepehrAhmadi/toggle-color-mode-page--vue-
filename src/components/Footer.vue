<template>
<footer :class="{ footer: true, dark: this.darkMode }">
    <span>2024 FiNiK development. All right reseved</span>
</footer>
</template>

<script>
export default {
    name: "Footer",
    props: {
        darkMode: Boolean
    }
}
</script>

<style scoped>

</style>
