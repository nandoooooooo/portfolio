<script setup>
  defineProps({
    href: String,
  })
</script>

<template>
  <div>
    <a :href="href">
      <slot />
    </a>
  </div>
</template>

<style scoped>
  div:first-of-type {
    margin: 2rem 0;
  }

  div {
    display: inline-block;
    margin: 2rem 0 2rem 1rem;
  }

  a {
    border-radius: 1rem;
    color: white;
    padding: .5rem 1rem;
    background: rgb(46, 181, 106);
    border: none;
    font-weight: bold;
    transition-duration: 0s;

    &:hover {
      border: solid 3px white;
      background: rgb(76, 201, 136);
    }

    &:active {
      background: rgb(36, 171, 96);
    }
  }
</style>