<script setup lang="ts">
import Notify from './components/notify.vue';

</script>

<template>
  <div class="dark:bg-gray-800">
    <div class="inline-block menu_principal">
      <Menu />
    </div>
    <div class="inline-block">
      <NuxtPage />
    </div>
    <Notify />
  </div>
</template>
