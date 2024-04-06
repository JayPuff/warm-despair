<script setup lang="ts">
  const should_render = ref(true)

 doSomething()
</script>

<template lang="pug">
h3(v-if="shouldRender" @click="changeTitle" class="page-title") {{ pageTitle }}
  p List below
  ul
    li(v-for="item in items" :key="item.id") {{ item.label }}
</template>