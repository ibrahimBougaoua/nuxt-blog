<template>
    <div>
        <Navbar />
        <Carousel />
    </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import Footer from '~/components/Footer.vue';

export default {
  name : 'default',
  components : {
    Navbar,
    Footer
  }
}
</script>