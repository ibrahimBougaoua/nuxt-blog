<template>
  
 <Header></Header>
 
 <SectionOne class="my-5"></SectionOne>
 <Sectiontwo class="my-5"></Sectiontwo>
</template>

<script>
  import Navbar from '~/components/Navbar.vue';
  import Header from '~/components/basic/Header.vue';
  import SectionOne from '~/components/SectionOne.vue';
  import Sectiontwo from "~/components/sectionTow.vue";
  
  export default {
    name: 'IndexPage',
    components : {
      Navbar,
      Header,
      SectionOne,
      Sectiontwo,
    }
  }
</script>