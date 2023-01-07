<script setup>
useHead({
    link: [ { rel: 'icon', type: 'image/png', href: 'favicon.ico' } ]
})
</script>

<template>
    <header>
        <nav>
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 relative z-50 flex justify-between py-8">
                <div class="relative z-10 flex items-center gap-16"><a class="flex items-center" aria-label="Home"
                                                                       href="/">
                    <img aria-hidden="true" class="h-10 w-10 flex-none mr-4" src="~/assets/svg/logo.svg"/>
                    <h1>Friends Quest</h1>
                </a>
                </div>
            </div>
        </nav>
    </header>

    <slot/>

    <footer class="border-t border-gray-200">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <div
                class="flex flex-col items-start justify-between gap-y-12 pt-8 lg:pt-16 pb-6 lg:flex-row lg:items-center py-8 lg:py-16">
                <div>
                    <div class="flex items-center text-gray-900">
                        <img aria-hidden="true" class="h-10 w-10 flex-none" src="~/assets/svg/logo.svg"/>
                        <div class="ml-4"><p class="text-base font-semibold">Friends Quest</p>
                            <p class="mt-1 text-sm">The unique travel experience.</p></div>
                    </div>
                </div>
            </div>
            <div
                class="flex flex-col items-center border-t border-gray-200 pt-8 pb-12 md:flex-row-reverse md:justify-between md:pt-6">
                <div class="flex gap-8 w-full justify-center md:w-auto">
                    <nuxt-link class="text-gray-700 transition-colors delay-150 hover:text-gray-900 hover:delay-[0ms]"
                               to="https://www.fh-salzburg.ac.at/en/imprint" target="_blank">Imprint
                    </nuxt-link>
                    <nuxt-link class="text-gray-700 transition-colors delay-150 hover:text-gray-900 hover:delay-[0ms]"
                               to="/data-privacy">Privacy Policy
                    </nuxt-link>
                </div>
                <p class="mt-6 text-sm text-gray-500 md:mt-0">© Copyright 2023. All rights reserved.</p></div>
        </div>
    </footer>
</template>

<style scoped>

</style>
