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
                            <div class="flex">
                                <svg class="w-10 h-10 mt-1" xmlns="http://www.w3.org/2000/svg" fill="none"
                                    viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round"
                                        d="M12.75 3.03v.568c0 .334.148.65.405.864l1.068.89c.442.369.535 1.01.216 1.49l-.51.766a2.25 2.25 0 01-1.161.886l-.143.048a1.107 1.107 0 00-.57 1.664c.369.555.169 1.307-.427 1.605L9 13.125l.423 1.059a.956.956 0 01-1.652.928l-.679-.906a1.125 1.125 0 00-1.906.172L4.5 15.75l-.612.153M12.75 3.031a9 9 0 00-8.862 12.872M12.75 3.031a9 9 0 016.69 14.036m0 0l-.177-.529A2.25 2.25 0 0017.128 15H16.5l-.324-.324a1.453 1.453 0 00-2.328.377l-.036.073a1.586 1.586 0 01-.982.816l-.99.282c-.55.157-.894.702-.8 1.267l.073.438c.08.474.49.821.97.821.846 0 1.598.542 1.865 1.345l.215.643m5.276-3.67a9.012 9.012 0 01-5.276 3.67m0 0a9 9 0 01-10.275-4.835M15.75 9c0 .896-.393 1.7-1.016 2.25" />
                                </svg>
                                <div class="ml-4">
                                    <h3 class="text-lg font-semibold text-gray-600">User pink</h3>
                                    <p class="font-medium text-gray-600">53 xu</p>
                                </div>
                            </div>
                            <div class="mb-6">
                                <h3 class="text-lg font-semibold text-gray-600 mt-6 my-3">Your board: Pink</h3>
                                <table class="table-auto mx-auto text-center">
                                    <tbody class="border-2 border-gray-600">
                                        <tr v-for="index in 9">
                                            <td class="bg-pink-500 text-white text-lg border px-4 py-3">1</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">20</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">30</td>
                                            <td class="bg-pink-500 text-white text-lg border px-2 py-3">40</td>
                                            <td class="bg-pink-500 text-white text-lg border px-5 py-3"></td>
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
                                <h3 class="font-semibold text-lg text-gray-600 mb-3">Action - Room owner only </h3>
                                <div class="mx-auto text-center">
                                    <button class="rounded-full bg-green-500 mx-1 text-white py-1 px-4">
                                        <svg class="w-5 h-5 mt-0.5 mr-2 float-left" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.348a1.125 1.125 0 010 1.971l-11.54 6.347a1.125 1.125 0 01-1.667-.985V5.653z" />
                                        </svg>
                                        <span>Play</span>
                                    </button>
                                    <button class="rounded-full bg-orange-500 mx-1 text-white py-1 px-3">
                                        <svg class="w-5 h-5 mt-0.5 mr-2 float-left" xmlns="http://www.w3.org/2000/svg"
                                            fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round"
                                                d="M10.34 15.84c-.688-.06-1.386-.09-2.09-.09H7.5a4.5 4.5 0 110-9h.75c.704 0 1.402-.03 2.09-.09m0 9.18c.253.962.584 1.892.985 2.783.247.55.06 1.21-.463 1.511l-.657.38c-.551.318-1.26.117-1.527-.461a20.845 20.845 0 01-1.44-4.282m3.102.069a18.03 18.03 0 01-.59-4.59c0-1.586.205-3.124.59-4.59m0 9.18a23.848 23.848 0 018.835 2.535M10.34 6.66a23.847 23.847 0 008.835-2.535m0 0A23.74 23.74 0 0018.795 3m.38 1.125a23.91 23.91 0 011.014 5.395m-1.014 8.855c-.118.38-.245.754-.38 1.125m.38-1.125a23.91 23.91 0 001.014-5.395m0-3.46c.495.413.811 1.035.811 1.73 0 .695-.316 1.317-.811 1.73m0-3.46a24.347 24.347 0 010 3.46" />
                                        </svg>
                                        <span>Voice</span>
                                    </button>
                                </div>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg text-gray-600 mb-3">Latest number</h3>
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
