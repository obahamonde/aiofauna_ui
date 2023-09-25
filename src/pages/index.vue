<script setup lang="ts">
useTitle('Home')
useFavicon("/favicon.png")
</script>
<template>
<Landing/>
<Toolbar/>
</template>

<route lang="yaml">
  meta:
    layout: home
</route>