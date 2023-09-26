<template>
    <div class="home_page">
        <div class="grid h-screen place-items-center bg-yellow-50">
            <div class="w-full h-full xl:h-3/4 xl:w-3/4 drop-shadow-lg bg-pink-50 rounded-lg py-20">
                <div class="text-center">
                    <h1 class="text-5xl font-bold drop-shadow-lg text-yellow-500">Lucky App</h1>
                    <p class="text-lg text-gray-500 font-medium">Wait, Lucky and Win</p>
                </div>
                <div class="flex justify-center items-center mt-4"><div class="flex justify-center items-center mt-10" data-v-inspector="app.vue:3:9"></div>
                    <svg class="w-40 h-40 text-gray-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                        stroke-width="1.5" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round"
                            d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                </div>
                <div class="flex justify-center items-center">
                    <form class="w-2/3 xl:w-1/3">
                        <div class="mb-2 block lg:flex gap-1 items-center" for="name">
                            <svg class="w-5 h-5 lg:w-8 lg:h-8 float-left mr-1 mt-0.5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                stroke-width="1.5" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z" />
                            </svg>
                            <span class="w-2/3">User's name:</span>
                            <input class="w-full border border-gray-500 py-2 px-4 rounded-xl" placeholder="User2508" type="text"
                                name="name" id="name">
                        </div>
                        <div class="mb-2 block lg:flex gap-1 items-center" for="room">
                            <svg class="w-5 h-5 lg:w-8 lg:h-8 float-left mr-1 mt-0.5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                stroke-width="1.5" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M15 9h3.75M15 12h3.75M15 15h3.75M4.5 19.5h15a2.25 2.25 0 002.25-2.25V6.75A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25v10.5A2.25 2.25 0 004.5 19.5zm6-10.125a1.875 1.875 0 11-3.75 0 1.875 1.875 0 013.75 0zm1.294 6.336a6.721 6.721 0 01-3.17.789 6.721 6.721 0 01-3.168-.789 3.376 3.376 0 016.338 0z" />
                            </svg>
                            <span class="w-2/3">Room's ID:</span>
                            <input class="w-full border border-gray-500 py-2 px-4 rounded-xl" placeholder="xhaskdfosfkk" type="text"
                                name="room" id="room">
                        </div>
                        <div class="flex justify-center items-center mt-4">
                            <button class="rounded-full bg-yellow-500 border-yellow-600 border-4 text-white py-2 px-6 mx-auto"
                                type="submit">
                                <svg class="w-6 h-6 float-left" xmlns="http://www.w3.org/2000/svg" fill="none"
                                    viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M15.59 14.37a6 6 0 01-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 006.16-12.12A14.98 14.98 0 009.631 8.41m5.96 5.96a14.926 14.926 0 01-5.841 2.58m-.119-8.54a6 6 0 00-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 00-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 01-2.448-2.448 14.9 14.9 0 01.06-.312m-2.24 2.39a4.493 4.493 0 00-1.757 4.306 4.493 4.493 0 004.306-1.758M16.5 9a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0z" />
                                </svg>
                                <span class="float-right ml-2 font-semibold">Play</span>
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>
