<template>
    <div class="home">
        <homeimageComp />
        <catagoryComp />
        <topsellingitemsComp />
        <productssectionComp />
        <topsellingitems2Comp />
        <newslettercontainerComp />
    </div>
</template>
  
<script>
import homeimageComp from './components/homeimage.vue'
import catagoryComp from './components/categorysection.vue'
import topsellingitemsComp from './components/topsellingitems.vue'
import productssectionComp from './components/productssection.vue'
import topsellingitems2Comp from './components/topsellingitems2.vue'
import newslettercontainerComp from './components/newslettercontainer.vue'

export default {
    name: 'HomeView',
    components: {
        homeimageComp, catagoryComp, topsellingitemsComp,topsellingitems2Comp, productssectionComp,newslettercontainerComp,
    }
}
</script>
  