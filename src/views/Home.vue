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
                          fill="#f7fafc"/>
                </svg>
            </div>
            <div class="container mx-auto px-4 pt-10 pb-48 text-center text-gray-200 md:w-1/2 md:px-0">
                <h2 class="text-2xl md:text-3xl font-semibold tracking-wide">Hi, <span class="bg-indigo-700 px-2">I'm Mosab</span>.
                    Nice to meet you.</h2>
                <p class="mt-4 text-gray-300 md:text-lg">I am software engineer. I spend my days building, designing,
                    developing web applications, playing video games mostly Minecraft, trying new technologies and
                    mentoring beginners and motivated programmers in my collage. I love talking and geeking about
                    programming and about what am building. And sharing programming goodness with the community ❤️.</p>
            </div>
        </div>

        <div class="container mx-auto -mt-32 px-4 md:px-0">
            <div class="flex flex-col md:flex-row bg-white shadow-lg rounded-lg">
                <div class="py-10 md:w-1/3">
                    <div class="flex flex-col items-center text-center">
                        <svg class="fill-current text-indigo-600 w-16" viewBox="0 0 24 24" fill="none"
                             xmlns="http://www.w3.org/2000/svg">
                            <path d="M5.0333 14.8284L6.44751 16.2426L10.6902 12L6.44751 7.75733L5.0333 9.17155L7.86172 12L5.0333 14.8284Z"
                                  fill="currentColor"/>
                            <path d="M15 14H11V16H15V14Z" fill="currentColor"/>
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                  d="M2 2C0.895431 2 0 2.89543 0 4V20C0 21.1046 0.89543 22 2 22H22C23.1046 22 24 21.1046 24 20V4C24 2.89543 23.1046 2 22 2H2ZM22 4H2L2 20H22V4Z"
                                  fill="currentColor"/>
                        </svg>
                        <h2 class="mt-4 text-2xl font-semibold tracking-wide">Back-end</h2>
                        <p class="px-8 mt-8 text-gray-600">I like to code things from scratch, and enjoy bringing ideas
                            to life in the browser.</p>
                        <p class="mt-8 text-indigo-600 text-lg">Things I enjoy building</p>
                        <p class="px-8 mt-4 text-gray-600">Web apps, APIs, Tools, Automating things</p>
                        <p class="mt-8 text-indigo-600 text-lg">Technology I use</p>
                        <p class="px-8 mt-4 text-gray-600">PHP, Laravel, Mysql</p>
                    </div>
                </div>
                <div class="border-t py-10 md:w-1/3">
                    <div class="flex flex-col items-center text-center">
                        <svg class="fill-current text-indigo-600 w-16" viewBox="0 0 24 24" fill="none"
                             xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                  d="M11 17H4C2.34315 17 1 15.6569 1 14V6C1 4.34315 2.34315 3 4 3H20C21.6569 3 23 4.34315 23 6V14C23 15.6569 21.6569 17 20 17H13V19H16C16.5523 19 17 19.4477 17 20C17 20.5523 16.5523 21 16 21H8C7.44772 21 7 20.5523 7 20C7 19.4477 7.44772 19 8 19H11V17ZM4 5H20C20.5523 5 21 5.44772 21 6V14C21 14.5523 20.5523 15 20 15H4C3.44772 15 3 14.5523 3 14V6C3 5.44772 3.44772 5 4 5Z"
                                  fill="currentColor"/>
                        </svg>
                        <h2 class="mt-4 text-2xl font-semibold tracking-wide">Front-end</h2>
                        <p class="px-8 mt-8 text-gray-600">I like to code things from scratch, and enjoy bringing ideas
                            to life in the browser.</p>
                        <p class="mt-8 text-indigo-600 text-lg">Things I enjoy designing</p>
                        <p class="px-8 mt-4 text-gray-600">Elegant and simple UI components</p>
                        <p class="mt-8 text-indigo-600 text-lg">Technology I use</p>
                        <p class="px-8 mt-4 text-gray-600">CSS, Javascript, Vue js</p>
                    </div>
                </div>
                <div class="border-t py-10 md:w-1/3">
                    <div class="flex flex-col items-center text-center">
                        <svg class="fill-current text-indigo-600 w-16" viewBox="0 0 24 24" fill="none"
                             xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                  d="M12.0122 5.57169L10.9252 4.48469C8.77734 2.33681 5.29493 2.33681 3.14705 4.48469C0.999162 6.63258 0.999162 10.115 3.14705 12.2629L11.9859 21.1017L11.9877 21.0999L12.014 21.1262L20.8528 12.2874C23.0007 10.1395 23.0007 6.65711 20.8528 4.50923C18.705 2.36134 15.2226 2.36134 13.0747 4.50923L12.0122 5.57169ZM11.9877 18.2715L16.9239 13.3352L18.3747 11.9342L18.3762 11.9356L19.4386 10.8732C20.8055 9.50635 20.8055 7.29028 19.4386 5.92344C18.0718 4.55661 15.8557 4.55661 14.4889 5.92344L12.0133 8.39904L12.006 8.3918L12.005 8.39287L9.51101 5.89891C8.14417 4.53207 5.92809 4.53207 4.56126 5.89891C3.19442 7.26574 3.19442 9.48182 4.56126 10.8487L7.10068 13.3881L7.10248 13.3863L11.9877 18.2715Z"
                                  fill="currentColor"/>
                        </svg>
                        <h2 class="mt-4 text-2xl font-semibold tracking-wide">Mentor</h2>
                        <p class="px-8 mt-8 text-gray-600">I like to code things from scratch, and enjoy bringing ideas
                            to life in the browser.</p>
                        <p class="mt-8 text-indigo-600 text-lg">Things I enjoy building</p>
                        <p class="px-8 mt-4 text-gray-600">Web apps, APIs, Tools, Automating things</p>
                        <p class="mt-8 text-indigo-600 text-lg">Technology I use</p>
                        <p class="px-8 mt-4 text-gray-600">PHP, Laravel, Mysql</p>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<script>

    export default {
        name: 'Home',
    }
</script>
