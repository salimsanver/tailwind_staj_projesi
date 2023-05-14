<template>
    <div>
        <div class=" px-28 flex h-16 mt-12 max-sm:-ml-24">
            <p class=" text-2xl font-bold max-sm:w-[96] max-sm:text-xl">Top Selling Items</p>
        </div>
     

        <carousel class="px-28 max-sm:px-4   " :autoplay="true" :nav="false" :margin="10" :loop="true" :responsive="{0:{items:2,nav:false,dots:false},700:{items:3,nav:false,dots:false},1100:{items:4,nav:false,dots:false},1460:{items:5,nav:false,dots:false},1570:{items:6,nav:false,dots:false}}">

<card img="bg-[url('@/assets/img/topsellingitems1.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems2.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems3.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems4.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems6.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
    <card img="bg-[url('@/assets/img/topsellingitems4.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems6.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
</carousel>
        <div class=" px-28 flex h-16 mt-20 max-sm:-ml-24">
            <p class=" text-2xl font-bold max-sm:w-[96] max-sm:text-xl">Top Selling Items</p>
        </div>

        <carousel class="px-28 max-sm:px-4 " :autoplay="true" :nav="false" :margin="10" :loop="true" :responsive="{0:{items:2,nav:false,dots:false},700:{items:3,nav:false,dots:false},1100:{items:4,nav:false,dots:false},1460:{items:5,nav:false,dots:false},1570:{items:6,nav:false,dots:false}}">

<card  img="bg-[url('@/assets/img/topsellingitems1.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems2.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems3.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems4.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems6.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
    <card img="bg-[url('@/assets/img/topsellingitems4.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems6.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
</carousel>
    </div>

</template>

<script>
import card from '@/components/card.vue'
import carousel from 'vue-owl-carousel'
export default {
    name: 'topsellingitems2Comp',
    components: {
        card,
        carousel
    },
}
</script>