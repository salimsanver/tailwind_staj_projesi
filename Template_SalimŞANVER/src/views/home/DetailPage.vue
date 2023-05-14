<template>
    <div id="detailPage">
       <navbarComp />
       
          
    <footerComp />
    <div>
            <p class="text-yellow-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero, magnam.</p>
          </div>

    </div>

</template>
<script>

import navbarComp from '@/partitions/navbar.vue'
import footerComp from '@/partitions/footer.vue'
export default {
  name: 'detailPage',
  components: {
    navbarComp,footerComp,
  }
}
</script>
