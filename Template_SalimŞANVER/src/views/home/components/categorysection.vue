<template>
   <div>
      
     <carousel class="px-28 max-sm:px-4 " :autoplay="true" :nav="false" :margin="20" :loop="true"
         :responsive="{ 0: { items: 2, nav: false, dots: false },  1536: { items: 8, nav: false, dots: false },1200:{items:5,nav:false,dots:false},950:{items:4,nav:false,dots:false},500:{items:3,nav:false,dots:false} }">

         <catagorycard :img="require('@/assets/img/gown.svg')" title="Gown" img2="bg-[url('@/assets/img/catagoryetek.png')]" />
         <catagorycard :img="require('@/assets/img/t-shirt.svg')" title="tops" img2="bg-[url('@/assets/img/tops.png')]" />
         <catagorycard :img="require('@/assets/img/jeans.svg')" title="dipleri" img2="bg-[url('@/assets/img/dipleri.png')]"/>
         <catagorycard :img="require('@/assets/img/cords.svg')" title="co-ords" img2="bg-[url('@/assets/img/co-ords.png')]"/>
         <catagorycard :img="require('@/assets/img/jacket.svg')" title="jackets" img2="bg-[url('@/assets/img/jackets.png')]"/>
         <catagorycard :img="require('@/assets/img/blzer.svg')" title="blazers" img2="bg-[url('@/assets/img/blazers.png')]"/>
         <catagorycard :img="require('@/assets/img/shapewear.svg')" title="shapewear" img2="bg-[url('@/assets/img/shapewear.png')]"/>
         <catagorycard :img="require('@/assets/img/sleepwear.svg')" title="dipleri" img2="bg-[url('@/assets/img/sleepwear.png')]"/>
         <catagorycard :img="require('@/assets/img/jacket.svg')" title="jackets"  img2="bg-[url('@/assets/img/jackets.png')]"/>


      </carousel>

   </div>

</template>
<script>
import carousel from 'vue-owl-carousel'
import catagorycard from '@/components/catagorycard.vue'
export default {
   name: 'categorySection',
   components: {
      catagorycard,
      carousel
   },
}
</script>
