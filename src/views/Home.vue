<template>
    <div>
        <header class="flex flex-col items-center text-center px-4 mt-16 md:px-0 md:mt-32">
            <h1 class="text-3xl md:text-5xl font-semibold">Software Engineer, Web Developer & Mentor</h1>
            <p class="text-gray-600 md:text-2xl font-light mt-4">I design and code beautifully simple things, and i love
                what I do.</p>
            <img class="mt-8 w-32 mt-16 md:w-56" :src="require('../assets/img/avatar.svg')" alt="Miaababikir Avatar">
        </header>
        <div class="bg-gray-800">
            <div>
                <svg viewBox="0 0 1280 198" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0 79.2L42.7667 85.8206C85.5333 92.1938 171.067 105.806 256.6 105.621C342.133 105.806 427.667 92.1938 513.2 105.621C598.733 118.8 684.267 158.4 769.8 165.021C855.333 171.394 940.867 145.406 1026.4 131.979C1111.93 118.8 1197.47 118.8 1240.23 118.8H1283V0H1240.23C1197.47 0 1111.93 0 1026.4 0C940.867 0 855.333 0 769.8 0C684.267 0 598.733 0 513.2 0C427.667 0 342.133 0 256.6 0C171.067 0 85.5333 0 42.7667 0H0V79.2Z"
                          fill="white"/>
                </svg>
            </div>
            <div class="container mx-auto px-4 py-10 text-center text-gray-200 md:w-1/2 md:px-0">
                <h2 class="text-2xl md:text-3xl font-semibold tracking-wide">Hi,  <span class="bg-indigo-700 px-2">I'm Mosab</span>. Nice to meet you.</h2>
                <p class="mt-4 text-gray-300 md:text-lg">I am software engineer. I spend my days building, designing, developing web applications, playing video games mostly Minecraft, trying new technologies and mentoring beginners and motivated programmers in my collage. I love talking and geeking about programming and about what am building. And sharing programming goodness with the community ❤️.</p>
            </div>
        </div>

    </div>
</template>

<script>

    export default {
        name: 'Home',
    }
</script>
