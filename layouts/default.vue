<script setup lang="ts"></script>

<template>
  <div>
    <TheHeader></TheHeader>
    <slot />
    <TheFooter></TheFooter>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: green;
}
</style>
