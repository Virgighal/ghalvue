<template>
  <div class="home">
    <HeaderGhal/>
    <HeroGhal/>
    <WomenBanner/>
    <InstaGhal/>
    <PartnerGhal/>
    <FooterGhal/>

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

import HeaderGhal from '@/components/HeaderGhal.vue'
import HeroGhal from '@/components/HeroGhal.vue'
import WomenBanner from '@/components/WomenBanner.vue'
import InstaGhal from '@/components/InstaGhal.vue'
import PartnerGhal from '@/components/PartnerGhal.vue'
import FooterGhal from '@/components/FooterGhal.vue'

export default {
  name: 'Home',
  components: {
    HeaderGhal,
    HeroGhal,
    WomenBanner,
    InstaGhal,
    PartnerGhal,
    FooterGhal
  }
};
</script>
