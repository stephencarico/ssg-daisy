<template>
  <div class="flex flex-col gap-6 m-6">
    <router-link to="/about" class="btn btn-primary">About</router-link>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="../assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<script setup>
import HelloWorld from "../components/HelloWorld.vue";
</script>
