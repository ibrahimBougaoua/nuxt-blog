<template>
    <div>
        <Navbar />
        <Carousel />
    </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';

export default {
  name : 'default',
  components : {
    Navbar
  }
}
</script>