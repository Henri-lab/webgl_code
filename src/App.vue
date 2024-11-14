<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import { onMounted } from 'vue';
//@ts-ignore
import test from './core/test';
onMounted(() => {
  test();
});
</script>

<template>
  <RouterView />
</template>

<style lang="scss"></style>

function onMounted(arg0: () => void) { throw new Error('Function not
implemented.'); } function onMounted(arg0: () => void) { throw new
Error('Function not implemented.'); }
