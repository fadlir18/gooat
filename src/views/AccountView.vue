<template>
  <TopNavigation />
  <div id="AccountView" class="max-w-4xl mx-auto ">
    <router-view/>
  </div>
  <FooterSection />
</template>

<style lang="scss">
  @import url(../css/808mansion-style.css);
  #AccountView{
    min-height: 70vh;
  }
</style>

<script setup>
  import TopNavigation from '@/components/structure/TopNavigation.vue'
  import FooterSection from '@/components/structure/FooterSection.vue'
</script>