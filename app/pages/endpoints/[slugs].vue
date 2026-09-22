<template>
    <div>
      <p>La ruta {{ $route.params.slugs }}</p>
    </div>
</template>

<script setup lang="ts">
  const route = useRoute()
</script>

<style lang="scss" scoped>

</style>