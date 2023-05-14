<template>
  <div id="app">
    <navbarComp />
    <router-view></router-view>
    <footerComp />
  </div>
</template>
<script>

import navbarComp from '@/partitions/navbar.vue'
import footerComp from '@/partitions/footer.vue'
export default {
  name: 'app',
  components: {
    navbarComp,footerComp,
  }
}
</script>
