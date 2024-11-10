<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TopBar from './components/TopBar.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <TopBar />
      <nav>
        <RouterLink to="/">Losowanie</RouterLink>
        <RouterLink to="/about">Twój List</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
