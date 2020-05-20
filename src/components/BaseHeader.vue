<template>
    <header class="flex flex-col items-center text-center px-4 mt-16 md:px-0 md:mt-32">
        <h1 class="text-3xl md:text-5xl font-semibold py-2 bounce-animation cursor-default">Software Engineer, Web Developer & Mentor</h1>
        <p class="text-gray-600 md:text-2xl font-light mt-4">I design and build beautifully simple things, and I love
            what I do.</p>
        <img class="mt-8 w-32 mt-16 md:w-56" :src="require('../assets/img/avatar.svg')" alt="Miaababikir Avatar">
    </header>
</template>

<script>
    export default {
        name: "BaseHeader"
    }
</script>

<style scoped>
    .bounce-animation:hover {
        animation: text-shadow 1.5s ease-in-out infinite;
    }

    @keyframes text-shadow {
        0% {
            transform: translateY(0);
            text-shadow:
                    0 0 0 #0c2ffb,
                    0 0 0 #2cfcfd,
                    0 0 0 #fb203b,
                    0 0 0 #fefc4b;
        }
        20% {
            transform: translateY(-1em);
            text-shadow:
                    0 0.125em 0 #0c2ffb,
                    0 0.25em 0 #2cfcfd,
                    0 -0.125em 0 #fb203b,
                    0 -0.25em 0 #fefc4b;
        }
        40% {
            transform: translateY(0.5em);
            text-shadow:
                    0 -0.0625em 0 #0c2ffb,
                    0 -0.125em 0 #2cfcfd,
                    0 0.0625em 0 #fb203b,
                    0 0.125em 0 #fefc4b;
        }
        60% {
            transform: translateY(-0.25em);
            text-shadow:
                    0 0.03125em 0 #0c2ffb,
                    0 0.0625em 0 #2cfcfd,
                    0 -0.03125em 0 #fb203b,
                    0 -0.0625em 0 #fefc4b;
        }
        80% {
            transform: translateY(0);
            text-shadow:
                    0 0 0 #0c2ffb,
                    0 0 0 #2cfcfd,
                    0 0 0 #fb203b,
                    0 0 0 #fefc4b;
        }
    }
    @media (prefers-reduced-motion: reduce) {
        * {
            animation: none !important;
            transition: none !important;
        }
    }
</style>