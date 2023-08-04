<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
     <nav class="flex justify-center mt-5">
        <RouterLink to ="/">Home</RouterLink>
        <RouterLink to="/about" class='mx-5'>About</RouterLink>
        <RouterLink to="/movies">Movies</RouterLink>
      </nav>
<RouterView />
</template>

<style scoped>

</style>
