<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>

import Header from '/components/basic/Header.vue';
import Footer from '/components/basic/Footer.vue';

export default {
  name : 'default',
  components : {
    Header,
    Footer
  }
}

</script>