<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBannerShayna />
    <InstaShayna />
    <PartnerLogoShayna />
    <FooterShayna />
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomenBannerShayna from '@/components/WomenBannerShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerLogoShayna from '@/components/PartnerLogoShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBannerShayna,
    InstaShayna,
    PartnerLogoShayna,
    FooterShayna
  }
}
</script>
