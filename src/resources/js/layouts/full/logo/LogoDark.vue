<template>
  <div class="logo">
    <RouterLink to="/">
      <img src="" alt="logo" height="60" />
    </RouterLink>
  </div>
</template>
<script setup>
import { ref } from 'vue';
import { RouterLink } from 'vue-router';
const primary = ref('rgb(var(--v-theme-primary))');
const secondary = ref('rgb(var(--v-theme-secondary))');
</script>
