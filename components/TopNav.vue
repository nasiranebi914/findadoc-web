<template>
    <div class="p-4 border-b flex justify-between items-center">
        <div class="font-semibold text-xl text-gray-800">
            <NuxtLink class="align-middle" to="/">
                <img class="inline align-middle pr-2"
                    src="../assets/images/logo-32-px-color.svg" />Find a Doc
            </NuxtLink>
        </div>
        <div class="flex gap-4 mx-6 absolute right-20">
            <NuxtLink to="/aboutPage" class="px-2 mx-auto">
                About Us
            </NuxtLink>

            <HamburgerComponent />
        </div>
        <LocaleSelector />
    </div>
</template>
