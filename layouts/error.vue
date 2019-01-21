<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">404 error page not found</h1>
    <h1 v-else>Something error without 404</h1>
    <p>This page shows layouts/error.vue</p>
    <nuxt-link to="/">Go to top</nuxt-link>
  </div>
</template>

<script>
export default {
  props: ['error']
}
</script>

<style lang="css">
</style>
