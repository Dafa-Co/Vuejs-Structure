<script setup lang="ts">
import ToggleTheme from "@/components/ToggleTheme.vue";
</script>

<template>
  <main>
    <header>auth header</header>
    <ToggleTheme />

    <RouterView />
    <footer>auth footer</footer>
  </main>
</template>
