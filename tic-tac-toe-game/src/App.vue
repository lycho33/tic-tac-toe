<script setup>
  import {ref, computed } from 'vue'

  const player = ref('X');
  const board = ref([
    ['', '', ''],
    ['', '', ''],
    ['', '', ''],
  ])
</script>

<template>
  <main class="pt-8 text-center">
    <h1 class="mb-8 text-3xl font-bold uppercase">Tic Tac Toe</h1>

    <h3 class="text-xl mb-4">Player {{ player }}'s turn</h3>
  </main>
</template>

<style>
</style>
