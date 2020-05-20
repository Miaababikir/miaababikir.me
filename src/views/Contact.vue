<template>
    <div class="container mx-auto px-4 md:px-0 mt-12">
        <h1 class="text-2xl md:text-4xl text-center font-semibold">Thanks for taking the time to reach out. How<br>can I
            help you today?</h1>
        <div class="max-w-4xl p-6 mx-auto md:mt-12">
            <form action="https://usebasin.com/f/2c0039e5aed2" method="POST">
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 mt-4">
                    <div class="col-span-2 md:col-span-1">
                        <label class="text-gray-700">Name</label>
                        <input type="text" name="name"
                               class="w-full mt-1 px-4 py-3 block rounded bg-gray-200 text-gray-800 border border-gray-300 focus:outline-none focus:bg-white">
                    </div>
                    <div class="col-span-2 md:col-span-1">
                        <label class="text-gray-700">Email</label>
                        <input type="email" name="email"
                               class="w-full mt-1 px-4 py-3 block rounded bg-gray-200 text-gray-800 border border-gray-300 focus:outline-none focus:bg-white">
                    </div>
                    <div class="col-span-2">
                        <label class="text-gray-700">Message</label>
                        <textarea name="message" class="w-full mt-1 px-4 py-3 block rounded bg-gray-200 text-gray-800 border border-gray-300 focus:outline-none focus:bg-white" rows="6"></textarea>
                    </div>
                </div>
                <div class="flex justify-center mt-8">
                    <button class="px-6 py-2 text-indigo-700 border-2 border-indigo-700 rounded-full rounded hover:bg-indigo-700 hover:text-gray-200 focus:outline-none">
                        Submit
                    </button>
                </div>
            </form>
        </div>
    </div>
</template>

<script>
    export default {}
</script>