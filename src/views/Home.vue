<template>
    <div>
        <header class="flex flex-col items-center text-center px-4 mt-16 md:px-0 md:mt-32">
            <h1 class="text-3xl md:text-5xl font-semibold">Software Engineer, Web Developer & Mentor</h1>
            <p class="text-gray-600 md:text-2xl font-light mt-4">I design and code beautifully simple things, and i love
                what I do.</p>
            <img class="mt-8 w-32 mt-16 md:w-56" :src="require('../assets/img/avatar.svg')" alt="Miaababikir Avatar">
        </header>

        <about />

        <skills />

    </div>
</template>

<script>

    import About from "../components/About";
    import Skills from "../components/Skills";
    export default {
        name: 'Home',
        components: {Skills, About},
    }
</script>
