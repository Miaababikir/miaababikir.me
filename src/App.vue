<template>
    <div id="app" class="min-h-screen font-roboto text-gray-800 bg-gray-100">
        <base-nav/>
        <router-view/>
    </div>
</template>

<style lang="scss" src="./assets/scss/app.scss"></style>
<script>
    import BaseNav from "./components/BaseNav";
    export default {
        components: {BaseNav}
    }
</script>