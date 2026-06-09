<script setup>
import { useRouter } from 'vue-router';

const router = useRouter();
</script>

<template>
  <div class="header">
    <p class="headerTitle" @click="router.push('/')">PIPELINE EXECUTOR - TFM</p>
  </div>
</template>

<style scoped src="./Header.css"></style>
