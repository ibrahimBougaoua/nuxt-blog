<template>
  <div>
    <p class="bg-orange-600 text-white text-xl text-center p-10">This page will be displayed at the /index route.</p>
  </div>
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