<template>
  <div>
    <navBar />
    <homeSection />
    <featureSection />
    <footerSection />
  </div>
</template>

<script>
  // @ is an alias to /src
  import navBar from '@/components/NavBar.vue'
  import homeSection from '@/components/HomeSection.vue'
  import featureSection from '@/components/FeatureSection.vue'
  import footerSection from '@/components/FooterSection.vue'
  
  export default {
    name: 'home',
    components: {
      navBar,
      homeSection,
      footerSection,
      featureSection,
    }
  }
</script>

