<template>
    <div class="container mx-auto text-center px-4 md:px-0 pb-20 mt-20">
        <img :src="require('../assets/img/collaborating.svg')" class="inline-block w-64 md:w-auto" alt="Collaboration">
        <div class="mt-12">
            <h2 class="text-2xl md:text-4xl font-semibold">Interested in collaborating or investing?</h2>
            <p class="text-gray-600 md:text-2xl font-light mt-1">I’m always open to opensource projects or partnership opportunities.</p>
            <div class="mt-8">
                <router-link to="contact"
                   class="px-8 py-3 border-2 border-indigo-700 text-indigo-700 rounded-full tracking-wider text-lg hover:bg-indigo-700 hover:text-gray-200">
                    Start a conversation
                </router-link>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Collaboration"
    }
</script>

<style scoped>

</style>