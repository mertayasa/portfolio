<!-- <script setup lang="ts">
import TheWelcome from "../components/TheWelcome.vue";
</script> -->

<template>
  <main>
    <button @click="count++" class="inline-block text-green-900 border border-green-500 bg-green-400 px-12 py-3 rounded font-bold transition-all hover:bg-transparent hover:text-green-500 focus:outline-none focus:ring active:text-green-500" type="button">Add More</button>
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