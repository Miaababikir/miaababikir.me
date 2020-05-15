<template>
    <div>
        <div class="h-1 w-full bg-indigo-600"></div>
        <nav class="container py-3 mx-auto">
            <div class="md:flex px-4 md:px-0 justify-between items-center">
                <div class="flex justify-between items-center">
                    <div class="flex items-center">
                        <img class="w-8" :src="require('../assets/img/logos/logo.svg')" alt="Miaababikir Logo">
                        <a class="ml-2 tracking-wide font-semibold text-lg" href="/home">Miaababikir</a>
                    </div>
                    <div class="md:hidden">
                        <button type="button" class="block" @click="isOpen = !isOpen">
                            <svg viewBox="0 0 24 24" class="h-6 w-6 fill-current">
                                <path d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
                            </svg>
                        </button>
                    </div>
                </div>
                <ul class="flex-col mt-3 md:flex-row md:items-center md:flex md:mt-0" :class="isOpen? 'flex' : 'hidden'">
                    <li class="py-1"><a href="#">Mentorship</a></li>
                    <li class="py-1 md:ml-3"><a href="#">Contact</a></li>
                    <li class="py-1 md:ml-3 flex">
                        <a href="https://twitter.com/miaababikir" target="_blank">
                            <svg width="16" height="17" viewBox="0 0 16 17" fill="none"
                                 xmlns="http://www.w3.org/2000/svg">
                                <g clip-path="url(#clip0)">
                                    <path d="M16 3.20723C15.4113 3.48313 14.7787 3.66893 14.1147 3.75268C14.7927 3.32407 15.3133 2.6449 15.558 1.83552C14.924 2.23247 14.2213 2.52103 13.4733 2.67657C12.8753 2.00303 12.0213 1.58215 11.0773 1.58215C8.958 1.58215 7.40067 3.66963 7.87933 5.83664C5.152 5.69236 2.73333 4.31291 1.114 2.21628C0.254 3.7738 0.668 5.81131 2.12933 6.84308C1.592 6.82478 1.08533 6.66924 0.643333 6.40954C0.607333 8.01491 1.69733 9.51683 3.276 9.85113C2.814 9.98345 2.308 10.0144 1.79333 9.91025C2.21067 11.2869 3.42267 12.2884 4.86 12.3166C3.48 13.4588 1.74133 13.9691 0 13.7523C1.45267 14.7355 3.17867 15.3091 5.032 15.3091C11.1267 15.3091 14.57 9.87506 14.362 5.00123C15.0033 4.51208 15.56 3.90189 16 3.20723Z"
                                          fill="#5A67D8"/>
                                </g>
                                <defs>
                                    <clipPath id="clip0">
                                        <rect width="16" height="16.8913" fill="white"/>
                                    </clipPath>
                                </defs>
                            </svg>
                        </a>
                        <a href="https://github.com/Miaababikir" class="ml-2" target="_blank">
                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none"
                                 xmlns="http://www.w3.org/2000/svg">
                                <path d="M8 0C3.58267 0 0 3.582 0 8C0 11.5347 2.292 14.5333 5.47133 15.5913C5.87067 15.6653 6 15.4173 6 15.2067V13.7173C3.77467 14.2013 3.31133 12.7733 3.31133 12.7733C2.94733 11.8487 2.42267 11.6027 2.42267 11.6027C1.69667 11.106 2.478 11.1167 2.478 11.1167C3.28133 11.1727 3.704 11.9413 3.704 11.9413C4.41733 13.164 5.57533 12.8107 6.032 12.606C6.10333 12.0893 6.31067 11.736 6.54 11.5367C4.76333 11.3333 2.89533 10.6473 2.89533 7.58267C2.89533 6.70867 3.208 5.99533 3.71933 5.43533C3.63667 5.23333 3.36267 4.41933 3.79733 3.318C3.79733 3.318 4.46933 3.10333 5.998 4.138C6.636 3.96067 7.32 3.872 8 3.86867C8.68 3.872 9.36467 3.96067 10.004 4.138C11.5313 3.10333 12.202 3.318 12.202 3.318C12.6373 4.42 12.3633 5.234 12.2807 5.43533C12.794 5.99533 13.104 6.70933 13.104 7.58267C13.104 10.6553 11.2327 11.332 9.45133 11.53C9.738 11.778 10 12.2647 10 13.0113V15.2067C10 15.4193 10.128 15.6693 10.534 15.5907C13.7107 14.5313 16 11.5333 16 8C16 3.582 12.418 0 8 0Z"
                                      fill="#5A67D8"/>
                            </svg>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script>
    export default {
        name: "BaseNav",
        data() {
            return {
                isOpen: false
            }
        }
    }
</script>