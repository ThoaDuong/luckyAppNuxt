<template>
    <div class="room_page">
        <div class="grid h-screen place-items-center bg-yellow-50">
            <div class="w-full h-full xl:w-3/4 rounded-lg">
                <div class="grid grid-cols-1 xl:grid-cols-5 mt-6">
                    <div class="col-span-2">
                        <div class="bg-white mb-6 rounded-xl drop-shadow-md py-3 px-6">
                            <div class="flex gap-4 max-w-full overflow-x-auto">
                                <div v-for="index in 5">
                                    <svg class="w-14 h-14 p-3 bg-blue-500 rounded-full text-white mx-auto"
                                        xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
                                    </svg>
                                    <label class="text-center text-md font-semibold text-yellow-600 mt-2">Pink</label>
                                </div>
                            </div>
                        </div>
                        <div class="bg-white mb-6 rounded-xl drop-shadow-md py-3 px-6">
                            <button class="py-1 px-4 rounded-full bg-yellow-400 float-right">
                                Manage coin
                            </button>
                            <h3 class="text-lg font-semibold text-gray-600">User pink</h3>
                            <p class="font-medium text-gray-600">0 coin</p>
                            <div class="mb-6">
                                <h3 class="text-lg font-semibold text-gray-600 mt-6 my-3">Your board: Pink</h3>
                                <table class="table-auto mx-auto text-center">
                                    <tbody class="border-2 border-gray-600">
                                        <tr>
                                            <td class="bg-pink-500 text-white text-lg border px-4 py-3">3</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">21</td>
                                            <td class="bg-gray-100 text-lg border px-5 py-3"></td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">40</td>
                                            <td class="bg-gray-100 text-lg border px-5 py-3"></td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">66</td>
                                            <td class="bg-gray-100 text-lg border px-5 py-3"></td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">89</td>
                                        </tr>
                                        <tr v-for="index in 8">
                                            <td class="bg-pink-500 text-white text-lg border px-4 py-3">1</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">20</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">30</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">40</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">50</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">60</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">70</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">80</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>


                    </div>
                    <div class="col-span-3 xl:ml-6">
                        <div class="bg-white mb-6 rounded-xl drop-shadow-md py-3 px-6">
                            <div class="flex gap-4 max-w-full overflow-x-auto">
                                <div>
                                    <svg class="w-14 h-14 p-3 bg-blue-500 rounded-full text-white mx-auto"
                                        xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M14.25 6.087c0-.355.186-.676.401-.959.221-.29.349-.634.349-1.003 0-1.036-1.007-1.875-2.25-1.875s-2.25.84-2.25 1.875c0 .369.128.713.349 1.003.215.283.401.604.401.959v0a.64.64 0 01-.657.643 48.39 48.39 0 01-4.163-.3c.186 1.613.293 3.25.315 4.907a.656.656 0 01-.658.663v0c-.355 0-.676-.186-.959-.401a1.647 1.647 0 00-1.003-.349c-1.036 0-1.875 1.007-1.875 2.25s.84 2.25 1.875 2.25c.369 0 .713-.128 1.003-.349.283-.215.604-.401.959-.401v0c.31 0 .555.26.532.57a48.039 48.039 0 01-.642 5.056c1.518.19 3.058.309 4.616.354a.64.64 0 00.657-.643v0c0-.355-.186-.676-.401-.959a1.647 1.647 0 01-.349-1.003c0-1.035 1.008-1.875 2.25-1.875 1.243 0 2.25.84 2.25 1.875 0 .369-.128.713-.349 1.003-.215.283-.4.604-.4.959v0c0 .333.277.599.61.58a48.1 48.1 0 005.427-.63 48.05 48.05 0 00.582-4.717.532.532 0 00-.533-.57v0c-.355 0-.676.186-.959.401-.29.221-.634.349-1.003.349-1.035 0-1.875-1.007-1.875-2.25s.84-2.25 1.875-2.25c.37 0 .713.128 1.003.349.283.215.604.401.96.401v0a.656.656 0 00.658-.663 48.422 48.422 0 00-.37-5.36c-1.886.342-3.81.574-5.766.689a.578.578 0 01-.61-.58v0z" />
                                    </svg>
                                    <label class="text-center text-md font-semibold text-yellow-600 mt-2">User123</label>
                                </div>
                                <div v-for="index in 10">
                                    <svg class="w-14 h-14 p-3 bg-blue-500 rounded-full text-white mx-auto"
                                        xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M14.25 6.087c0-.355.186-.676.401-.959.221-.29.349-.634.349-1.003 0-1.036-1.007-1.875-2.25-1.875s-2.25.84-2.25 1.875c0 .369.128.713.349 1.003.215.283.401.604.401.959v0a.64.64 0 01-.657.643 48.39 48.39 0 01-4.163-.3c.186 1.613.293 3.25.315 4.907a.656.656 0 01-.658.663v0c-.355 0-.676-.186-.959-.401a1.647 1.647 0 00-1.003-.349c-1.036 0-1.875 1.007-1.875 2.25s.84 2.25 1.875 2.25c.369 0 .713-.128 1.003-.349.283-.215.604-.401.959-.401v0c.31 0 .555.26.532.57a48.039 48.039 0 01-.642 5.056c1.518.19 3.058.309 4.616.354a.64.64 0 00.657-.643v0c0-.355-.186-.676-.401-.959a1.647 1.647 0 01-.349-1.003c0-1.035 1.008-1.875 2.25-1.875 1.243 0 2.25.84 2.25 1.875 0 .369-.128.713-.349 1.003-.215.283-.4.604-.4.959v0c0 .333.277.599.61.58a48.1 48.1 0 005.427-.63 48.05 48.05 0 00.582-4.717.532.532 0 00-.533-.57v0c-.355 0-.676.186-.959.401-.29.221-.634.349-1.003.349-1.035 0-1.875-1.007-1.875-2.25s.84-2.25 1.875-2.25c.37 0 .713.128 1.003.349.283.215.604.401.96.401v0a.656.656 0 00.658-.663 48.422 48.422 0 00-.37-5.36c-1.886.342-3.81.574-5.766.689a.578.578 0 01-.61-.58v0z" />
                                    </svg>
                                    <label class="text-center text-md font-semibold text-yellow-600 mt-2">Username{{ index
                                    }}</label>
                                </div>
                            </div>
                        </div>
                        <div
                            class="bg-white mb-6 rounded-xl drop-shadow-md text-9xl font-bold text-yellow-600 py-24 text-center">
                            25
                        </div>
                        <div class="bg-white mb-6 rounded-xl drop-shadow-md py-3 px-6">
                            <div>
                                <span class="float-right italic text-gray-400">Room owner only</span>
                                <h3 class="font-semibold text-lg text-gray-600 mb-3">Game action </h3>
                                <div class="mx-auto text-center">
                                    <button class="rounded-full bg-orange-500 mx-1 text-white py-1 px-3">
                                        <svg class="w-5 h-5 mt-0.5 mr-2 float-left" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M9.75 9.75l4.5 4.5m0-4.5l-4.5 4.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                        </svg>

                                        <span>Stop & Clear</span>
                                    </button>
                                    <button class="rounded-full bg-green-500 mx-1 text-white py-1 px-4">
                                        <svg class="w-5 h-5 mt-0.5 mr-2 float-left" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.348a1.125 1.125 0 010 1.971l-11.54 6.347a1.125 1.125 0 01-1.667-.985V5.653z" />
                                        </svg>
                                        <span>Next Number</span>
                                    </button>
                                </div>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg text-gray-600 mb-3">Called number</h3>
                                <!-- <div class="flex flex-wrap">
                                        <span class="bg-blue-400 rounded-full p-2 text-white mr-1 mt-1">30</span>
                                    </div> -->
                                <div class="flex flex-wrap h-auto max-h-52 overflow-y-auto">
                                    <span v-for="index in 90" class="bg-blue-400 rounded-full py-1 px-3 text-white mr-1 mt-1">
                                        {{ index }} </span>
                                </div>        
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
