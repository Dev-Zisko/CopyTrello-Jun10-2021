<template>
    <footer>
        <span>Con amor &amp; <a href="//vuejs.org">Vue.js</a> by Zisko</span>
    </footer>
</template>

<script>
export default {
    name: 'app-footer'
}
</script>

<style scoped>
    footer {
        box-sizing: border-box;
        background-color: #cfd8dc;
        bottom: 0;
        left: 0;
        padding: 1rem;
        position: absolute;
        top: 120%;
        height: 45px;
        width: 100%;
    }

    a {
        text-decoration: none;
        color: #546e7a;
    }
</style>