<script setup>
const { $hello } = useNuxtApp();
</script>
<template>
  <div>
    <h1>Main Page</h1>
    <h2>{{ $hello('World') }}</h2>
  </div>
</template>