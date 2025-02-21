<script setup>

import HeroHeader from "@/components/HeroHeader.vue";
import Header from "@/components/Header.vue";
</script>

<template>
  <Header />
  <main>
    <HeroHeader />
  </main>
</template>

<style>
  html, body {
    margin: 0;
    padding: 0;
    background: rgb(36, 36, 36);
  }

  ::selection {
    color: white;
    background: rgb(76, 201, 136);
  }

  h1 {
    color: rgb(219, 216, 213);
    font-weight: 650;
    font-size: 3rem;
  }

  mark {
    color: rgb(76, 201, 136);
    background: none;
  }
</style>
