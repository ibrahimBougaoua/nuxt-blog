<template>
    <div class="container mx-auto px-4">
      <Navbar />
      <slot />
    </div>
</template>

<script>
import Header from '~/components/basic/Header.vue';

export default {
  name : 'default',
  components : {
    Header,
  }
}
</script>