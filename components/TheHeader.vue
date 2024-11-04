<script setup></script>

<template>
  <header class="flex justify-center pt-5 pb-5 flex justify-around flex-wrap">
    <div class="logo">
      <NuxtLink to="/"><h1 class="text-white">Nuxt Movies</h1></NuxtLink>
    </div>
    <form action="" v-on:click.prevent class="flex gap-4">
      <input type="text" name="SearchMovie" id="" class="rounded-xl w-64 h-8" />
      <button
        class="rounded-xl bg-yellow-400 p-1 w-24 h-8 hover:bg-green-400 transition duration-500"
      >
        Search
      </button>
    </form>
    <div class="favorites_block cursor-pointer flex flex-col items-center">
      <img
        src="/public/favorite_add.png"
        alt=""
        class="cursor-pointer h-8 w-8"
      />
      <span class="text-white hover:text-green-400 transition duration-500"
        >Favorites</span
      >
    </div>
  </header>
</template>

<style lang="scss" scoped></style>
