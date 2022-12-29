<template>
  <nav class="navbar">
    <ol class="nav-items">
      <li class="nav-item">
        <RouterLink to="/">Home</RouterLink>
      </li>
      <li class="nav-item">
        <RouterLink to="/about">About</RouterLink>
      </li>
    </ol>
  </nav>
</template>

<script setup>
import { RouterLink } from "vue-router";
</script>
