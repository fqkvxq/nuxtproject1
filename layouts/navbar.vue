<template>
  <div class="navbar">
    <Header />
      <nuxt/>
    <Footer />
  </div>
</template>

<script>

import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

export default {
  name: 'navbar',
  components: {
    Header,
    Footer
  }
}
</script>
