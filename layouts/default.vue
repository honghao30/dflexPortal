<template>
  <div>
    <Header />
    <slot />
    <Quckbar />
  </div>
</template>

<script setup>
import Header from '../components/common/Header.vue';
import Quckbar from '../components/common/Quckbar.vue';
</script>
