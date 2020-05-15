<template>
    <div id="app" class="font-roboto text-gray-800">
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