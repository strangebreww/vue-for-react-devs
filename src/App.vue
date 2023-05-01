<script setup>
import { ref } from 'vue';

const product = ref('Socks');
</script>

<template>
  <h1>{{ product }}</h1>
</template>