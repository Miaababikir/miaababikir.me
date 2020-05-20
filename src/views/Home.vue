<template>
    <div>
        <base-header />
        <about/>
        <skills/>
        <projects/>
        <collaboration/>

        <base-footer />

    </div>
</template>

<script>

    import About from "../components/About";
    import Skills from "../components/Skills";
    import Projects from "../components/Projects";
    import Collaboration from "../components/Collaboration";
    import BaseFooter from "../components/BaseFooter";
    import BaseHeader from "../components/BaseHeader";

    export default {
        name: 'Home',
        components: {BaseHeader, BaseFooter, Collaboration, Projects, Skills, About},
    }
</script>
