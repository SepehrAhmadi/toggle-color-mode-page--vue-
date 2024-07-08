<template>
    <main :class="{ main: true, dark: this.darkMode }">
        <h1 class="main-title">Fun facts about React</h1>
        <ul class="main-facts">
            <li>Was first released in 2014.</li>
            <li>Was originally created by Evan You.</li>
            <li>Vue is faster than Angular.</li>
            <li>Vue is a free and open source project.</li>
            <li>Vue has one of the best async components / code splitting patterns support.</li>
        </ul>
    </main>
</template>

<script>
export default {
    name: "MainContent",
    props: {
        darkMode: Boolean
    }
}
</script>

<style scoped>

</style>
