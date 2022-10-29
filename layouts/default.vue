<template>
  <div>
    <Header />
    <Features />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>

import Header from '~/components/basic/Header.vue';
import Footer from '~/components/basic/Footer.vue';
import Features from '~/components/Features.vue';

export default {
  name : 'default',
  components : {
    Header,
    Features,
    Footer
  }
}
</script>