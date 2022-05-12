<template>
  <div>
    <default-nav />
    <slot />
    <!-- <default-footer /> -->
  </div>
</template>

<script setup>
import DefaultFooter from './DefaultFooter.vue'
import DefaultNav from './DefaultNav.vue'
</script>

<style lang="scss">
/* Sticky footer */
html {
  position: relative;
  min-height: 100%;
}

.footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 60px; /* Footer height */
  line-height: 60px; /* Vertically center the text */
  background-color: $gray-100;
  text-align: center;
}
</style>
