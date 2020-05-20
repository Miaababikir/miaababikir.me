<template>
    <div>
        <div class="flex flex-col items-center text-center px-4 mt-16 md:px-0 md:mt-32">
            <h1 class="text-2xl md:text-4xl font-semibold">Coming soon🔥...</h1>
            <!--        <p class="text-gray-600 md:text-2xl font-light mt-4">But if you need a mentor, then email me maybe.</p>-->
            <img class="mt-8  mt-16" :src="require('../assets/img/mentor.svg')" alt="Mentorship">
        </div>

        <base-footer class="mt-12" />
    </div>

</template>

<script>
    import BaseFooter from "../components/BaseFooter";

    export default {
        components: {BaseFooter}
    }
</script>