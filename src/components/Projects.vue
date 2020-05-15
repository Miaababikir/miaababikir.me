<template>
    <div>
        <div class="bg-gray-800 text-gray-200 text-center pt-20 mt-20">
            <div class="container mx-auto px-4 md:px-0">
                <h2 class="text-4xl font-semibold">My Recent Work</h2>
                <p class="text-gray-400 text-lg">Here are a few design projects I've worked on recently. Want to see
                    more?
                    <a href="https://github.com/Miaababikir" class="text-indigo-500">Github</a></p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-12">
                    <div class="bg-gray-300 text-gray-800 rounded-lg relative overflow-hidden image-card">
                        <div class="flex flex-col items-center py-8">
                            <img :src="require('../assets/img/meraki.svg')" alt="Meraki UI Logo" class="w-24">
                            <p class="mt-4 font-semibold text-2xl">Meraki UI</p>
                        </div>
                        <div class="absolute flex flex-col items-center justify-center bg-gray-900 py-8 px-12 w-full h-full left-0 top-0 overlay">
                            <p class="text-gray-200 text-lg">Beautiful Tailwind css components that support RTL out of
                                the box & fully responsive.</p>
                            <a href="https://merakiui.com/"
                               class="mt-4 px-8 py-2 border-2 border-indigo-700 rounded-full text-gray-200 tracking-wider text-lg hover:bg-indigo-700">Visit
                                Site</a>
                        </div>
                    </div>

                    <div class="bg-gray-300 text-gray-800 rounded-lg relative overflow-hidden image-card">
                        <div class="flex flex-col items-center py-8">
                            <img :src="require('../assets/img/nothingworks.png')" alt="Nothing Works Logo" class="w-24">
                            <p class="mt-4 font-semibold text-2xl">Nothing works</p>
                        </div>
                        <div class="absolute flex flex-col items-center justify-center bg-gray-900 py-8 px-12 w-full h-full left-0 top-0 overlay">
                            <p class="text-gray-200 text-lg">My personal blog, I write about our industry from time to
                                time. </p>
                            <a href="https://nothingworks.netlify.com/"
                               class="mt-4 px-8 py-2 border-2 border-indigo-700 rounded-full text-gray-200 tracking-wider text-lg hover:bg-indigo-700">Visit
                                Site</a>
                        </div>
                    </div>

                    <div class="bg-gray-300 text-gray-800 rounded-lg relative overflow-hidden image-card">
                        <div class="flex flex-col items-center py-8">
                            <img :src="require('../assets/img/modulo.svg')" alt="Modulo Logo" class="w-20">
                            <p class="mt-4 font-semibold text-2xl">Modulo</p>
                        </div>
                        <div class="absolute flex flex-col items-center justify-center bg-gray-900 py-8 px-12 w-full h-full left-0 top-0 overlay">
                            <p class="text-gray-200 text-lg">Modulo provides form endpoints as a service, so your simple
                                sites can stay simple.</p>
                            <a href="http://modulo-app.herokuapp.com/"
                               class="mt-4 px-8 py-2 border-2 border-indigo-700 rounded-full text-gray-200 tracking-wider text-lg hover:bg-indigo-700">Visit
                                Site</a>
                        </div>
                    </div>
                </div>

                <div class="flex justify-center mt-12">
                    <a href="https://github.com/Miaababikir"
                       class="flex items-center px-8 py-3 border-2 border-indigo-700 rounded-full text-gray-200 tracking-wider text-lg hover:bg-indigo-700">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12 0C5.374 0 0 5.373 0 12C0 17.302 3.438 21.8 8.207 23.387C8.806 23.498 9 23.126 9 22.81V20.576C5.662 21.302 4.967 19.16 4.967 19.16C4.421 17.773 3.634 17.404 3.634 17.404C2.545 16.659 3.717 16.675 3.717 16.675C4.922 16.759 5.556 17.912 5.556 17.912C6.626 19.746 8.363 19.216 9.048 18.909C9.155 18.134 9.466 17.604 9.81 17.305C7.145 17 4.343 15.971 4.343 11.374C4.343 10.063 4.812 8.993 5.579 8.153C5.455 7.85 5.044 6.629 5.696 4.977C5.696 4.977 6.704 4.655 8.997 6.207C9.954 5.941 10.98 5.808 12 5.803C13.02 5.808 14.047 5.941 15.006 6.207C17.297 4.655 18.303 4.977 18.303 4.977C18.956 6.63 18.545 7.851 18.421 8.153C19.191 8.993 19.656 10.064 19.656 11.374C19.656 15.983 16.849 16.998 14.177 17.295C14.607 17.667 15 18.397 15 19.517V22.81C15 23.129 15.192 23.504 15.801 23.386C20.566 21.797 24 17.3 24 12C24 5.373 18.627 0 12 0Z"
                                  fill="#EDF2F7"/>
                        </svg>
                        <span class="ml-2">More on Github</span>
                    </a>
                </div>
            </div>
        </div>
        <svg viewBox="0 0 1280 198" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M-3 79.2L39.7667 85.8206C82.5333 92.1938 168.067 105.806 253.6 105.621C339.133 105.806 424.667 92.1938 510.2 105.621C595.733 118.8 681.267 158.4 766.8 165.021C852.333 171.394 937.867 145.406 1023.4 131.979C1108.93 118.8 1194.47 118.8 1237.23 118.8H1280V0H1237.23C1194.47 0 1108.93 0 1023.4 0C937.867 0 852.333 0 766.8 0C681.267 0 595.733 0 510.2 0C424.667 0 339.133 0 253.6 0C168.067 0 82.5333 0 39.7667 0H-3V79.2Z"
                  fill="#2D3748"/>
        </svg>
    </div>

</template>

<script>
    export default {
        name: "Projects"
    }
</script>

<style scoped>
    .overlay {
        transition: all 0.4s ease;
        opacity: 0;
    }

    .image-card:hover .overlay {
        opacity: 1;
    }
</style>