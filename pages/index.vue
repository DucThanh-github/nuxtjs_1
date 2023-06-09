<template>
    <div>Shop PC_LAPTOP_MOBILE</div>

    <ul>
        <li>
            <nuxt-link class="hover:opacity-75 hover:text-red-500" :to="'/danhsach/laptop'"> LapTop </nuxt-link>
        </li>
        <li>
            <nuxt-link> Mobile </nuxt-link>
        </li>
    </ul>
</template>

<script lang="ts">

definePageMeta({
    layout: 'homelayout'
})
</script>