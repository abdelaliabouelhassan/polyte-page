<template>
 <div class="indexPage">
   <FirstSection />
   <SecondSection />
 </div>
</template>

<script>
import FirstSection from '@/components/sections/FirstSection.vue'
import SecondSection from '@/components/sections/SecondSection.vue'
export default {
  name: 'IndexPage',
  components: {
    FirstSection,
    SecondSection
  }
}
</script>



<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
  .indexPage {
    width: 100%;
    height: 100%;
  }
  body {
    padding: 0px !important;
    margin: 0px !important;
  }
</style>