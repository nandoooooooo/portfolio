<script setup>

import Button from "@/components/Button.vue";
</script>

<template>
  <div>
    <h1 class="introduction-title">Buenos<mark>,</mark> Mundo<mark>!</mark></h1>
    <h2>I'm an <mark>IT Apprentice</mark> at getAbstract. I'm <mark>17 years</mark> old, and my favorite hobby is playing <mark>Volleyball.</mark></h2>
    <Button href="#about">More About Me</Button>
    <Button href="#skills">Those are My Skills</Button>
  </div>
</template>

<style scoped>
  .introduction-title {
    color: white;
    font-size: 6rem;
    margin-bottom: -1rem;
  }
</style>