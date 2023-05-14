<template>
    <div class="">
       <maincontainerComp/>
<carousel class="px-28  max-sm:px-2 " :autoplay="true" :nav="false" :margin="40" :loop="true" :responsive="{0:{items:2,nav:false,dots:false},768:{items:3,nav:false,dots:false},1300:{items:4,nav:false,dots:false},1460:{items:5,nav:false,dots:false},1570:{items:5,nav:false,dots:false}}">

<card :img="require('@/assets/img/detailimg1.png')" title="Vegetable" title1="Fresh Bread and Pastry Flour 200 g" title2=" (34) " title3="$12.68" title4="$14.69 " title5="Add"/>
<card  :img="require('@/assets/img/detailsimg2.png')" title="Vegetable" title1="Fresh Bread and Pastry Flour 200 g" title2=" (34) " title3="$12.68" title4="$14.69 " title5="Add"/>
<card  :img="require('@/assets/img/detailsimg3.png') " title="Vegetable" title1="Fresh Bread and Pastry Flour 200 g" title2=" (34) " title3="$12.68" title4="$14.69 " title5="Add"/>
<card :img="require('@/assets/img/detailsimg4.png')" title="Vegetable" title1="Fresh Bread and Pastry Flour 200 g" title2=" (34) " title3="$12.68" title4="$14.69 " title5="Add"/>
<card :img="require('@/assets/img/detailimg5.png')" title="Vegetable" title1="Fresh Bread and Pastry Flour 200 g" title2=" (34) " title3="$12.68" title4="$14.69 " title5="Add"/>
<card :img="require('@/assets/img/detailsimg3.png')" title="Vegetable" title1="Fresh Bread and Pastry Flour 200 g" title2=" (34) " title3="$12.68" title4="$14.69" title5="Add"/>
</carousel>
    </div>
</template>
  
<script>

import carousel from 'vue-owl-carousel'
import card from '../detail/components/productbox.vue'
import maincontainerComp from '../detail/components/maincontainer.vue'
export default {
    name: 'detailPage',
    components: { card,
        carousel,maincontainerComp,

        
    }
}
</script>
  