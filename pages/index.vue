<template>
  <div class="flex w-screen justify-center">
    <div class="grid">
      <div class="text-center">Shop PC_LAPTOP_MOBILE</div>
      <ul class="flex justify-between">
        <li>
          <nuxt-link
          class="font-bold text-green-400 hover:opacity-75 hover:text-red-500"

            :to="'/danhsach/laptop'"
          >
            LapTop
          </nuxt-link>
        </li>
        <li>
          <nuxt-link
            class="font-bold text-green-400 hover:opacity-75 hover:text-red-500"
          :to="'/danhsach/mobile'"
            >
            Mobile
          </nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
definePageMeta({
  layout: "homelayout",
});
</script>