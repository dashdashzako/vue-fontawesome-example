<script setup lang="ts">
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faHandshake } from '@fortawesome/free-regular-svg-icons'
</script>

<template>
  <main>
    Hello
    <FontAwesomeIcon :icon="faHandshake" />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}
</style>
