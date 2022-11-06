<template>
    <div class="container mx-auto px-4">
      <Header />
      <slot />
      <SectionOne />
      <sectionTow />
      <sectionThree />
      <SectionFour />
      <Features />
      <Footer />
    </div>
</template>

<script>
import Header from '~/components/basic/Header.vue';
import SectionOne from '~/components/SectionOne.vue';
import sectionTow from '~/components/sectionTow.vue';
import sectionThree from '~/components/sectionThree.vue';
import SectionFour from '~/components/SectionFour.vue';
import Features from '~/components/Features.vue';
import Footer from '~/components/basic/Footer.vue';

export default {
  name : 'default',
  components : {
    Header,
    Features,
    SectionOne,
    sectionTow,
    sectionThree,
    SectionFour,
    Footer
  }
}
</script>