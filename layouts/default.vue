<template>
    <div class="container mx-auto px-4">
      <Header />
      <Features />
      <Nuxt />
      <Footer />
    </div>
</template>

<script>
import Header from '~/components/basic/Header.vue';
import Features from '~/components/Features.vue';
import Footer from '~/components/basic/Footer.vue';

export default {
  name : 'default',
  components : {
    Header,
    Features,
    Footer
  }
}
</script>