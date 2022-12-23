<script setup lang="ts">
import TheWelcome from "../components/TheWelcome.vue";
</script>

<template>
  <main>
    <TheWelcome />
    <button @click="count++" type="button">+</button>
    <h3>{{ count }}</h3>
  </main>
</template>

<script lang="ts">
  export default {
    data() {
      return {
        count: 33
      }
    }
  }
</script>