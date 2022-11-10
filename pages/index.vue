<template>
  <Header />
  <SectionOne />
</template>

<script>
  import Navbar from '~/components/Navbar.vue';
  import Header from '~/components/basic/Header.vue';
  import SectionOne from '~/components/SectionOne.vue';
  
  export default {
    name: 'IndexPage',
    components : {
      Navbar,
      Header,
    }
  }
</script>