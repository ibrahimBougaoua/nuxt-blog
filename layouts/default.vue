<template>
    <div class="container mx-auto px-4">
      <Navbar />
      <slot />
    </div>
    
    <Footer/>

</template>

<script>
import Header from '~/components/basic/Header.vue';
import Footer from '~/components/basic/Footer.vue';
export default {
  name : 'default',
  components : {
    Header,Footer
  }
}
</script>