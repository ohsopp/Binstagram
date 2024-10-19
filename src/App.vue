<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink> | 
      <RouterLink to="/about">About</RouterLink> |
      <RouterLink to="/qwer">QWER</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>
