<script setup>
const image = ref(1)
const features = ref([ {
    title: 'Invite friends',
    description: 'Invite your friends to join the fun! More friends means more competition and more memories to be made.',
}, {
    title: 'Share footprints',
    description: 'Playfully share the most special moments by capturing only one image per location.'
}, {
    title: 'React to footprints',
    description: 'Reacting to a friend\'s footprint will allow you to express your feelings on it.'
}
])
</script>

<template>
    <main>
        <div class="overflow-hidden py-20 lg:pb-32 xl:pb-36" style="height: 100vh">
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                <div class="lg:grid lg:grid-cols-12 lg:gap-x-8 lg:gap-y-20">
                    <div class="relative z-10 mx-auto max-w-2xl lg:col-span-7 lg:max-w-none lg:pt-6 xl:col-span-6">
                        <h1 class="text-4xl font-medium tracking-tight text-gray-900">The unique travel experience.</h1>
                        <p class="mt-6 text-lg text-gray-600">Travel the world and capture the most special moments as
                            footprints on your globe. Follow the footprints of your friends and react on their memories.
                            When you are too far away to see whats behind the footprint just listen to the sounds behind
                            the memory.</p>
                        <div class="mt-8 flex gap-x-6 gap-y-4">
                            <a href="/#">
                                <img width="150" src="~/assets/images/product-hunt-logo-horizontal-orange.png"
                                     style="background: transparent;"/>
                            </a>
                        </div>
                    </div>
                    <div class="relative mt-10 sm:mt-20 lg:col-span-5 lg:row-span-2 lg:mt-0 xl:col-span-6">
                        <div
                            class="absolute left-1/2 top-4 h-[1026px] w-[1026px] -translate-x-1/3 stroke-gray-300/70 [mask-image:linear-gradient(to_bottom,white_20%,transparent_75%)] sm:top-16 sm:-translate-x-1/2 lg:-top-16 lg:ml-12 xl:-top-14 xl:ml-0"
                        >
                            <svg viewBox="0 0 1026 1026" fill="none" aria-hidden="true"
                                 class="absolute inset-0 h-full w-full animate-spin-slow">
                                <path
                                    d="M1025 513c0 282.77-229.23 512-512 512S1 795.77 1 513 230.23 1 513 1s512 229.23 512 512Z"
                                    stroke="#D4D4D4" stroke-opacity="0.7"></path>
                                <path d="M513 1025C230.23 1025 1 795.77 1 513" stroke="#af4e21"
                                      stroke-linecap="round"></path>
                                <defs>
                                    <linearGradient id=":r3:-gradient-1" x1="1" y1="513" x2="1" y2="1025"
                                                    gradientUnits="userSpaceOnUse">
                                        <stop stop-color="#06b6d4"></stop>
                                        <stop offset="1" stop-color="#06b6d4" stop-opacity="0"></stop>
                                    </linearGradient>
                                </defs>
                            </svg>
                            <svg viewBox="0 0 1026 1026" fill="none" aria-hidden="true"
                                 class="absolute inset-0 h-full w-full animate-spin-reverse-slower">
                                <path
                                    d="M913 513c0 220.914-179.086 400-400 400S113 733.914 113 513s179.086-400 400-400 400 179.086 400 400Z"
                                    stroke="#D4D4D4" stroke-opacity="0.7"></path>
                                <path d="M913 513c0 220.914-179.086 400-400 400" stroke="url(#:r3:-gradient-2)"
                                      stroke-linecap="round"></path>
                                <defs>
                                    <linearGradient id=":r3:-gradient-2" x1="913" y1="513" x2="913" y2="913"
                                                    gradientUnits="userSpaceOnUse">
                                        <stop stop-color="#af4e21"></stop>
                                        <stop offset="1" stop-color="#af4e21" stop-opacity="0"></stop>
                                    </linearGradient>
                                </defs>
                            </svg>
                        </div>
                        <div
                            class="-mx-4 h-[448px] px-9 [mask-image:linear-gradient(to_bottom,white_90%,transparent)] sm:mx-0 lg:absolute lg:-inset-x-10 lg:-top-10 lg:-bottom-56 lg:h-auto lg:px-0 lg:pt-10 xl:-bottom-42">
                            <div class="relative aspect-[366/729] mx-auto max-w-[366px]">
                                <div
                                    class="absolute inset-y-[calc(1/729*100%)] right-[calc(5/729*100%)] left-[calc(7/729*100%)] rounded-[calc(58/366*100%)/calc(58/729*100%)] shadow-2xl"></div>
                                <div
                                    class="absolute top-[calc(23/729*100%)] left-[calc(23/366*100%)] grid h-[calc(686/729*100%)] w-[calc(318/366*100%)] transform grid-cols-1 overflow-hidden bg-gray-900 pt-[calc(23/318*100%)]">
                                    <img v-if="image === 1" src="~/assets/images/header.jpeg"/>
                                </div>
                                <svg viewBox="0 0 366 729" aria-hidden="true"
                                     class="pointer-events-none absolute inset-0 h-full w-full fill-gray-100">
                                    <path
                                        fill="#F2F2F2"
                                        fill-rule="evenodd"
                                        clip-rule="evenodd"
                                        d="M300.092 1c41.22 0 63.223 21.99 63.223 63.213V184.94c-.173.184-.329.476-.458.851.188-.282.404-.547.647-.791.844-.073 2.496.257 2.496 2.157V268.719c-.406 2.023-2.605 2.023-2.605 2.023a7.119 7.119 0 0 1-.08-.102v394.462c0 41.213-22.001 63.212-63.223 63.212h-95.074c-.881-.468-2.474-.795-4.323-.838l-33.704-.005-.049.001h-.231l-.141-.001c-2.028 0-3.798.339-4.745.843H66.751c-41.223 0-63.223-21.995-63.223-63.208V287.739c-.402-.024-2.165-.23-2.524-2.02v-.973A2.039 2.039 0 0 1 1 284.62v-47.611c0-.042.001-.084.004-.126v-.726c0-1.9 1.652-2.23 2.496-2.157l.028.028v-16.289c-.402-.024-2.165-.23-2.524-2.02v-.973A2.039 2.039 0 0 1 1 214.62v-47.611c0-.042.001-.084.004-.126v-.726c0-1.9 1.652-2.23 2.496-2.157l.028.028v-26.041a2.26 2.26 0 0 0 .093-.236l-.064-.01a3.337 3.337 0 0 1-.72-.12l-.166-.028A2 2 0 0 1 1 135.62v-24.611a2 2 0 0 1 1.671-1.973l.857-.143v-44.68C3.528 22.99 25.53 1 66.75 1h233.341ZM3.952 234.516a5.481 5.481 0 0 0-.229-.278c.082.071.159.163.228.278Zm89.99-206.304A4.213 4.213 0 0 0 89.727 24H56.864C38.714 24 24 38.708 24 56.852v618.296C24 693.292 38.714 708 56.864 708h250.272c18.15 0 32.864-14.708 32.864-32.852V56.852C340 38.708 325.286 24 307.136 24h-32.864a4.212 4.212 0 0 0-4.213 4.212v2.527c0 10.235-8.3 18.532-18.539 18.532H112.48c-10.239 0-18.539-8.297-18.539-18.532v-2.527Z"
                                    ></path>
                                    <rect x="154" y="29" width="56" height="5" rx="2.5" fill="#D4D4D4"></rect>
                                </svg>
                                <img alt="" src="~/assets/svg/phone-frame.svg" width="366" height="729" decoding="async"
                                     data-nimg="1" class="pointer-events-none absolute inset-0 h-full w-full"
                                     style="color: transparent;"/>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <section id="features" aria-label="Features of Friends Quest" class="bg-gray-900 py-20 sm:py-32">
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-3xl">
                    <h2 class="text-3xl font-medium tracking-tight text-white">Travel, share and follow footprints. Try
                        it for yourself.</h2>
                    <p class="mt-2 text-lg text-gray-400">
                        Battle your friends in travelling around the world, find places you have never been before and
                        share memories with your friends in the most unique way.
                    </p>
                </div>
            </div>
            <div class="mt-16 md:hidden">
                <div
                    class="-mb-4 flex snap-x snap-mandatory -space-x-4 overflow-x-auto overscroll-x-contain scroll-smooth pb-4 [scrollbar-width:none] sm:-space-x-6 [&::-webkit-scrollbar]:hidden">
                    <div class="w-full flex-none snap-center px-4 sm:px-6">
                        <div class="relative transform overflow-hidden rounded-2xl bg-gray-800 px-5 py-6">
                            <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2">
                                <svg viewBox="0 0 558 558" width="558" height="558" fill="none" aria-hidden="true">
                                    <defs>
                                        <linearGradient id=":r5:" x1="79" y1="16" x2="105" y2="237"
                                                        gradientUnits="userSpaceOnUse">
                                            <stop stop-color="#af4e21"></stop>
                                            <stop offset="1" stop-color="#af4e21" stop-opacity="0"></stop>
                                        </linearGradient>
                                    </defs>
                                    <path opacity=".2"
                                          d="M1 279C1 125.465 125.465 1 279 1s278 124.465 278 278-124.465 278-278 278S1 432.535 1 279Z"
                                          stroke="#af4e21"></path>
                                    <path d="M1 279C1 125.465 125.465 1 279 1" stroke="url(#:r5:)"
                                          stroke-linecap="round"></path>
                                </svg>
                            </div>
                            <div class="relative aspect-[366/729] relative mx-auto w-full max-w-[366px]">
                                <div
                                    class="absolute inset-y-[calc(1/729*100%)] right-[calc(5/729*100%)] left-[calc(7/729*100%)] rounded-[calc(58/366*100%)/calc(58/729*100%)] shadow-2xl"></div>
                                <div
                                    class="absolute top-[calc(23/729*100%)] left-[calc(23/366*100%)] grid h-[calc(686/729*100%)] w-[calc(318/366*100%)] transform grid-cols-1 overflow-hidden bg-gray-900 pt-[calc(23/318*100%)]">
                                    <transition name="slide-up">
                                        <img v-if="image === 1" src="~/assets/images/screens/1.jpeg" style="position: absolute;"/>
                                        <img v-else-if="image === 2" src="~/assets/images/screens/2.jpeg" style="position: absolute;"/>
                                        <img v-else-if="image === 3" src="~/assets/images/screens/3.jpeg" style="position: absolute;"/>
                                    </transition>
                                </div>
                                <svg viewBox="0 0 366 729" aria-hidden="true"
                                     class="pointer-events-none absolute inset-0 h-full w-full fill-gray-100">
                                    <path
                                        fill="#F2F2F2"
                                        fill-rule="evenodd"
                                        clip-rule="evenodd"
                                        d="M300.092 1c41.22 0 63.223 21.99 63.223 63.213V184.94c-.173.184-.329.476-.458.851.188-.282.404-.547.647-.791.844-.073 2.496.257 2.496 2.157V268.719c-.406 2.023-2.605 2.023-2.605 2.023a7.119 7.119 0 0 1-.08-.102v394.462c0 41.213-22.001 63.212-63.223 63.212h-95.074c-.881-.468-2.474-.795-4.323-.838l-33.704-.005-.049.001h-.231l-.141-.001c-2.028 0-3.798.339-4.745.843H66.751c-41.223 0-63.223-21.995-63.223-63.208V287.739c-.402-.024-2.165-.23-2.524-2.02v-.973A2.039 2.039 0 0 1 1 284.62v-47.611c0-.042.001-.084.004-.126v-.726c0-1.9 1.652-2.23 2.496-2.157l.028.028v-16.289c-.402-.024-2.165-.23-2.524-2.02v-.973A2.039 2.039 0 0 1 1 214.62v-47.611c0-.042.001-.084.004-.126v-.726c0-1.9 1.652-2.23 2.496-2.157l.028.028v-26.041a2.26 2.26 0 0 0 .093-.236l-.064-.01a3.337 3.337 0 0 1-.72-.12l-.166-.028A2 2 0 0 1 1 135.62v-24.611a2 2 0 0 1 1.671-1.973l.857-.143v-44.68C3.528 22.99 25.53 1 66.75 1h233.341ZM3.952 234.516a5.481 5.481 0 0 0-.229-.278c.082.071.159.163.228.278Zm89.99-206.304A4.213 4.213 0 0 0 89.727 24H56.864C38.714 24 24 38.708 24 56.852v618.296C24 693.292 38.714 708 56.864 708h250.272c18.15 0 32.864-14.708 32.864-32.852V56.852C340 38.708 325.286 24 307.136 24h-32.864a4.212 4.212 0 0 0-4.213 4.212v2.527c0 10.235-8.3 18.532-18.539 18.532H112.48c-10.239 0-18.539-8.297-18.539-18.532v-2.527Z"
                                    ></path>
                                    <rect x="154" y="29" width="56" height="5" rx="2.5" fill="#D4D4D4"></rect>
                                </svg>
                                <img
                                    alt=""
                                    src="~/assets/svg/phone-frame.svg"
                                    width="366"
                                    height="729"
                                    decoding="async"
                                    data-nimg="1"
                                    class="pointer-events-none absolute inset-0 h-full w-full"
                                    loading="lazy"
                                    style="color: transparent;"
                                />
                            </div>
                            <div class="absolute inset-x-0 bottom-0 bg-gray-800/95 p-6 backdrop-blur sm:p-10">
                                <h3 class="mt-6 text-sm font-semibold text-white sm:text-lg">
                                    {{ features[image - 1].title }}</h3>
                                <p class="mt-2 text-sm text-gray-400">{{ features[image - 1].description }}</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="mt-6 flex justify-center gap-3">
                    <button type="button" class="relative h-0.5 w-4 rounded-full"
                            :class="{ 'bg-gray-300': image === 1, 'bg-gray-500': image !== 1 }"
                            aria-label="Go to slide 1" @click="image = 1"><span
                        class="absolute -inset-x-1.5 -inset-y-3"></span></button>
                    <button type="button" class="relative h-0.5 w-4 rounded-full"
                            :class="{ 'bg-gray-300': image === 2, 'bg-gray-500': image !== 2 }"
                            aria-label="Go to slide 2" @click="image = 2"><span
                        class="absolute -inset-x-1.5 -inset-y-3"></span></button>
                    <button type="button" class="relative h-0.5 w-4 rounded-full"
                            :class="{ 'bg-gray-300': image === 3, 'bg-gray-500': image !== 3 }"
                            aria-label="Go to slide 3" @click="image = 3"><span
                        class="absolute -inset-x-1.5 -inset-y-3"></span></button>
                </div>
            </div>
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 hidden md:mt-20 md:block">
                <div class="grid grid-cols-12 items-center gap-8 lg:gap-16 xl:gap-24">
                    <div class="relative z-10 order-last col-span-6 space-y-6" role="tablist"
                         aria-orientation="vertical">
                        <div class="relative rounded-2xl transition-colors hover:bg-gray-800/30">
                            <div class="relative z-10 p-8 rounded-2xl" :class="{ 'bg-gray-800': image === 1 }">
                                <svg viewBox="0 0 32 32" aria-hidden="true" class="h-8 w-8">
                                    <circle cx="16" cy="16" r="16" fill="#A3A3A3" fill-opacity="0.2"></circle>
                                    <path fill-rule="evenodd" clip-rule="evenodd"
                                          d="M16 23a3 3 0 100-6 3 3 0 000 6zm-1 2a4 4 0 00-4 4v1a2 2 0 002 2h6a2 2 0 002-2v-1a4 4 0 00-4-4h-2z"
                                          fill="#a3a3a3"></path>
                                    <path
                                        fill-rule="evenodd"
                                        clip-rule="evenodd"
                                        d="M5 4a4 4 0 014-4h14a4 4 0 014 4v24a4.002 4.002 0 01-3.01 3.877c-.535.136-.99-.325-.99-.877s.474-.98.959-1.244A2 2 0 0025 28V4a2 2 0 00-2-2h-1.382a1 1 0 00-.894.553l-.448.894a1 1 0 01-.894.553h-6.764a1 1 0 01-.894-.553l-.448-.894A1 1 0 0010.382 2H9a2 2 0 00-2 2v24a2 2 0 001.041 1.756C8.525 30.02 9 30.448 9 31s-.455 1.013-.99.877A4.002 4.002 0 015 28V4z"
                                        fill="#A3A3A3"
                                    ></path>
                                </svg>
                                <h3 class="mt-6 text-lg font-semibold text-white">
                                    <button
                                        class="text-left [&:not(:focus-visible)]:focus:outline-none"
                                        id="headlessui-tabs-tab-:r9:"
                                        role="tab"
                                        type="button"
                                        aria-selected="true"
                                        tabindex="0"
                                        data-headlessui-state="selected"
                                        aria-controls="headlessui-tabs-panel-:rn:"
                                        @click="image = 1"
                                    >
                                        <span class="absolute inset-0 rounded-2xl"></span>{{ features[0].title }}
                                    </button>
                                </h3>
                                <p class="mt-2 text-sm text-gray-400">{{ features[0].description }}</p>
                            </div>
                        </div>
                        <div class="relative rounded-2xl transition-colors hover:bg-gray-800/30">
                            <div class="relative z-10 p-8 rounded-2xl" :class="{ 'bg-gray-800': image === 2 }">
                                <svg viewBox="0 0 32 32" aria-hidden="true" class="h-8 w-8">
                                    <path
                                        fill-rule="evenodd"
                                        clip-rule="evenodd"
                                        d="M9 0a4 4 0 00-4 4v24a4 4 0 004 4h14a4 4 0 004-4V4a4 4 0 00-4-4H9zm0 2a2 2 0 00-2 2v24a2 2 0 002 2h14a2 2 0 002-2V4a2 2 0 00-2-2h-1.382a1 1 0 00-.894.553l-.448.894a1 1 0 01-.894.553h-6.764a1 1 0 01-.894-.553l-.448-.894A1 1 0 0010.382 2H9z"
                                        fill="#a3a3a3"
                                    ></path>
                                    <path d="M12 25l8-8m0 0h-6m6 0v6" stroke="#a3a3a3" stroke-width="2"
                                          stroke-linecap="round"></path>
                                    <circle cx="16" cy="16" r="16" fill="#A3A3A3" fill-opacity="0.2"></circle>
                                </svg>
                                <h3 class="mt-6 text-lg font-semibold text-white">
                                    <button class="text-left [&:not(:focus-visible)]:focus:outline-none"
                                            id="headlessui-tabs-tab-:ra:" role="tab" type="button" aria-selected="false"
                                            tabindex="-1" @click="image = 2">
                                        <span class="absolute inset-0 rounded-2xl"></span>{{ features[1].title }}
                                    </button>
                                </h3>
                                <p class="mt-2 text-sm text-gray-400">
                                    {{ features[1].description }}
                                </p>
                            </div>
                        </div>
                        <div class="relative rounded-2xl transition-colors hover:bg-gray-800/30">
                            <div class="relative z-10 p-8 rounded-2xl" :class="{ 'bg-gray-800': image === 3 }">
                                <svg viewBox="0 0 32 32" fill="none" aria-hidden="true" class="h-8 w-8">
                                    <defs>
                                        <linearGradient id=":rb:-gradient" x1="14" y1="14.5" x2="7" y2="17"
                                                        gradientUnits="userSpaceOnUse">
                                            <stop stop-color="#737373"></stop>
                                            <stop offset="1" stop-color="#D4D4D4" stop-opacity="0"></stop>
                                        </linearGradient>
                                    </defs>
                                    <circle cx="16" cy="16" r="16" fill="#A3A3A3" fill-opacity="0.2"></circle>
                                    <path
                                        fill-rule="evenodd"
                                        clip-rule="evenodd"
                                        d="M5 4a4 4 0 014-4h14a4 4 0 014 4v13h-2V4a2 2 0 00-2-2h-1.382a1 1 0 00-.894.553l-.448.894a1 1 0 01-.894.553h-6.764a1 1 0 01-.894-.553l-.448-.894A1 1 0 0010.382 2H9a2 2 0 00-2 2v24a2 2 0 002 2h4v2H9a4 4 0 01-4-4V4z"
                                        fill="#A3A3A3"
                                    ></path>
                                    <path d="M7 22c0-4.694 3.5-8 8-8" stroke="url(#:rb:-gradient)" stroke-width="2"
                                          stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path
                                        d="M21 20l.217-5.513a1.431 1.431 0 00-2.85-.226L17.5 21.5l-1.51-1.51a2.107 2.107 0 00-2.98 0 .024.024 0 00-.005.024l3.083 9.25A4 4 0 0019.883 32H25a4 4 0 004-4v-5a3 3 0 00-3-3h-5z"
                                        fill="#A3A3A3"
                                    ></path>
                                </svg>
                                <h3 class="mt-6 text-lg font-semibold text-white">
                                    <button class="text-left [&:not(:focus-visible)]:focus:outline-none"
                                            id="headlessui-tabs-tab-:rc:" role="tab" type="button" aria-selected="false"
                                            tabindex="-1" data-headlessui-state="" @click="image = 3">
                                        <span class="absolute inset-0 rounded-2xl"></span>{{ features[2].title }}
                                    </button>
                                </h3>
                                <p class="mt-2 text-sm text-gray-400">{{ features[2].description }}</p>
                            </div>
                        </div>
                    </div>
                    <div class="relative col-span-6">
                        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2">
                            <svg viewBox="0 0 558 558" width="558" height="558" fill="none" aria-hidden="true"
                                 class="animate-spin-slower">
                                <defs>
                                    <linearGradient id=":rd:" x1="79" y1="16" x2="105" y2="237"
                                                    gradientUnits="userSpaceOnUse">
                                        <stop stop-color="#af4e21"></stop>
                                        <stop offset="1" stop-color="#af4e21" stop-opacity="0"></stop>
                                    </linearGradient>
                                </defs>
                                <path opacity=".2"
                                      d="M1 279C1 125.465 125.465 1 279 1s278 124.465 278 278-124.465 278-278 278S1 432.535 1 279Z"
                                      stroke="#af4e21"></path>
                                <path d="M1 279C1 125.465 125.465 1 279 1" stroke="url(#:rd:)"
                                      stroke-linecap="round"></path>
                            </svg>
                        </div>
                        <div class="relative aspect-[366/729] z-10 mx-auto w-full max-w-[366px]">
                            <div
                                class="absolute inset-y-[calc(1/729*100%)] right-[calc(5/729*100%)] left-[calc(7/729*100%)] rounded-[calc(58/366*100%)/calc(58/729*100%)] shadow-2xl"></div>
                            <div
                                class="absolute top-[calc(23/729*100%)] left-[calc(23/366*100%)] flex justify-center items-center h-[calc(686/729*100%)] w-[calc(318/366*100%)] transform overflow-hidden bg-gray-900 pt-[calc(23/318*100%)]">
                                <transition name="slide-up">
                                    <img v-if="image === 1" src="~/assets/images/screens/1.jpeg" style="position: absolute;"/>
                                    <img v-else-if="image === 2" src="~/assets/images/screens/2.jpeg" style="position: absolute;"/>
                                    <img v-else-if="image === 3" src="~/assets/images/screens/3.jpeg" style="position: absolute;"/>
                                </transition>
                            </div>
                            <svg viewBox="0 0 366 729" aria-hidden="true"
                                 class="pointer-events-none absolute inset-0 h-full w-full fill-gray-100">
                                <path
                                    fill="#F2F2F2"
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M300.092 1c41.22 0 63.223 21.99 63.223 63.213V184.94c-.173.184-.329.476-.458.851.188-.282.404-.547.647-.791.844-.073 2.496.257 2.496 2.157V268.719c-.406 2.023-2.605 2.023-2.605 2.023a7.119 7.119 0 0 1-.08-.102v394.462c0 41.213-22.001 63.212-63.223 63.212h-95.074c-.881-.468-2.474-.795-4.323-.838l-33.704-.005-.049.001h-.231l-.141-.001c-2.028 0-3.798.339-4.745.843H66.751c-41.223 0-63.223-21.995-63.223-63.208V287.739c-.402-.024-2.165-.23-2.524-2.02v-.973A2.039 2.039 0 0 1 1 284.62v-47.611c0-.042.001-.084.004-.126v-.726c0-1.9 1.652-2.23 2.496-2.157l.028.028v-16.289c-.402-.024-2.165-.23-2.524-2.02v-.973A2.039 2.039 0 0 1 1 214.62v-47.611c0-.042.001-.084.004-.126v-.726c0-1.9 1.652-2.23 2.496-2.157l.028.028v-26.041a2.26 2.26 0 0 0 .093-.236l-.064-.01a3.337 3.337 0 0 1-.72-.12l-.166-.028A2 2 0 0 1 1 135.62v-24.611a2 2 0 0 1 1.671-1.973l.857-.143v-44.68C3.528 22.99 25.53 1 66.75 1h233.341ZM3.952 234.516a5.481 5.481 0 0 0-.229-.278c.082.071.159.163.228.278Zm89.99-206.304A4.213 4.213 0 0 0 89.727 24H56.864C38.714 24 24 38.708 24 56.852v618.296C24 693.292 38.714 708 56.864 708h250.272c18.15 0 32.864-14.708 32.864-32.852V56.852C340 38.708 325.286 24 307.136 24h-32.864a4.212 4.212 0 0 0-4.213 4.212v2.527c0 10.235-8.3 18.532-18.539 18.532H112.48c-10.239 0-18.539-8.297-18.539-18.532v-2.527Z"
                                ></path>
                                <rect x="154" y="29" width="56" height="5" rx="2.5" fill="#D4D4D4"></rect>
                            </svg>
                            <img
                                alt=""
                                src="~/assets/svg/phone-frame.svg"
                                width="366"
                                height="729"
                                decoding="async"
                                data-nimg="1"
                                class="pointer-events-none absolute inset-0 h-full w-full"
                                loading="lazy"
                                style="color: transparent;"
                            />
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="faqs" aria-labelledby="faqs-title" class="border-t border-gray-200 py-20 sm:py-32">
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                <div class="mx-auto max-w-2xl lg:mx-0">
                    <h2 id="faqs-title" class="text-3xl font-medium tracking-tight text-gray-900">Frequently asked
                        questions</h2>
                    <p class="mt-2 text-lg text-gray-600">If you have anything else you want to ask, <a
                        class="text-gray-900 underline" href="mailto:app.friendsquest@gmail.com">reach out to us</a>.
                    </p>
                </div>
                <ul role="list"
                    class="mx-auto mt-16 grid max-w-2xl grid-cols-1 gap-8 sm:mt-20 lg:max-w-none lg:grid-cols-3">
                    <li>
                        <ul role="list" class="space-y-10">
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">What is the purpose of the
                                    app?</h3>
                                <p class="mt-4 text-sm text-gray-700">The app allows you to create digital footprints,
                                    which are combinations of an image and audio that represent a moment or experience
                                    in your life at a specific location.</p>
                            </li>
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">How do I create a digital
                                    footprint?</h3>
                                <p class="mt-4 text-sm text-gray-700">
                                    To create a digital footprint, first click the plus button at the globe. An audio
                                    message to go along with the image is recorded in the background automatically.
                                    Finally, save your digital footprint. Afterwards it's visible for your friends.
                                </p>
                            </li>
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">Can I customize my digital
                                    footprint?</h3>
                                <p class="mt-4 text-sm text-gray-700">Yes, you can customize the image and audio that
                                    make up your digital footprint. You can also add captions or a description to help
                                    describe your footprint.</p>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <ul role="list" class="space-y-10">
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">Can I share my digital
                                    footprint with others?</h3>
                                <p class="mt-4 text-sm text-gray-700">Yes, you're footprints are automatically shared
                                    with your friends. In the future you can also choose to make your footprint private
                                    and only visible to yourself.</p>
                            </li>
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">Is there a limit to how many
                                    digital footprints I can create?</h3>
                                <p class="mt-4 text-sm text-gray-700">There is no limit to the number of digital
                                    footprints you can create. Feel free to capture as many moments and experiences as
                                    you'd like.</p>
                            </li>
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">Is it possible to delete a
                                    digital footprint that I have created?</h3>
                                <p class="mt-4 text-sm text-gray-700">
                                    Yes, it is possible to delete a digital footprint that you have created. You can do
                                    this from your profile page or by accessing the footprint directly.
                                </p>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <ul role="list" class="space-y-10">
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">Is the app free to use?</h3>
                                <p class="mt-4 text-sm text-gray-700">The app is free to download and use.</p>
                            </li>
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">How do I report a problem or
                                    issue with the app?</h3>
                                <p class="mt-4 text-sm text-gray-700">If you encounter a problem or issue with the app,
                                    you can report it by contacting us via <a
                                        class="text-gray-900 underline"
                                        href="mailto:app.friendsquest@gmail.com">e-mail</a>.</p>
                            </li>
                            <li>
                                <h3 class="text-lg font-semibold leading-6 text-gray-900">How can I receive points
                                    within the app?</h3>
                                <p class="mt-4 text-sm text-gray-700">
                                    There are several ways to receive points. In the near future there even will be
                                    bonus points for completing certain tasks. The best way to know how to receive
                                    points is to try it out. Wouldn't it be boring if we just tell you how to get
                                    points? It's like revealing a magic trick. You don't do that ;)
                                </p>
                            </li>
                        </ul>
                    </li>
                </ul>
            </div>
        </section>
    </main>
</template>

<style>
@import "~/assets/css/fonts.css";

@keyframes spin-reverse {
    0% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(-360deg);
    }
}

@keyframes spin {
    0% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(360deg);
    }
}

html {
    font-family: "TexGyreHeros", system-ui;
}

.animate-spin-reverse-slower {
    animation: spin-reverse 6s linear infinite;
}

.animate-spin-slow {
    animation: spin 4s linear infinite;
}

.animate-spin-slower {
    animation: spin 6s linear infinite;
}

.slide-up-enter-active,
.slide-up-leave-active {
    transition: all 1s ease-out;
}

.slide-up-enter-from {
    opacity: 0;
    transform: translateY(100px);
}

.slide-up-leave-to {
    opacity: 0;
    transform: translateY(-100px);
}
</style>
