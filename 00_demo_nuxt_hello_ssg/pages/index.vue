<script setup>

const { x, y } = useMouse()

</script>

<template>
  <div>
    <h1>Welcome to the homepage</h1>
    <p>{{ x }} {{ y }}</p>
  </div>
</template>
