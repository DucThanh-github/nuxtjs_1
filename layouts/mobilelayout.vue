<template>
    <div class="mt-8">
            <header class="text-center mb-4 font-bold">
                    MOBILE PAGE
            </header>
            <nuxt-link class=" block text-center mb-4 font-bold  hover:opacity-75 hover:text-red-500"  :to="'/'">HOME</nuxt-link>
            <slot />
        </div>
    </template>