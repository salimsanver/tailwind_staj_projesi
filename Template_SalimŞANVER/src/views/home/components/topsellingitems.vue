<template>
    <div>
        <div class=" px-28 flex h-16 mt-12 max-sm:-ml-24 max-sm:mt-8">
            <p class=" text-2xl font-bold max-sm:w-[96] max-sm:text-xl">Top Selling Items</p>
        </div>
     

<carousel class="px-28 max-sm:px-4  " :autoplay="true" :nav="false" :margin="10" :loop="true" :responsive="{0:{items:2,nav:false,dots:false},600:{items:4,nav:false,dots:false},1000:{items:5,nav:false,dots:false},1460:{items:6,nav:false,dots:false},1570:{items:7,nav:false,dots:false}}">

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




        <div class=" flex max-xl:flex-wrap  justify-between items-center px-28 bg-cover bg-center gap-6 mt-8    max-sm:px-4">
            <div class="      w-8/12 max-xl:w-full max-md:w-full max-lg:w-full ">
                <img class="rounded-xl h-60    max-sm:max-sm:object-cover  w-full " src="@/assets/img/searchimage.jpg" alt="">
                <div class=" inset-0 hover:bg-gray-200 opacity-50 rounded-xl hover:transition-all duration-500 w-full">
                </div>
                <p class="absolute -mt-56 px-8 font-bold text-3xl italic text-cyan-700 max-sm:text-2xl max-sm:pt-2 max-lg:text-2xl ">Get Ready To</p>
                <p class="absolute -mt-44 px-8  text-3xl italic max-sm:pt-0 max-sm:text-xl max-lg:text-2xl">TAKE ON THE DAY!</p>
                <p class="absolute -mt-32 px-8   italic  max-sm:w-11/12 max-sm:text-sm max-lg:text-xs w-96 ">In publishing and graphic design, Lorem ipsum is a
                    placeholder text commonly used to demonstrate.</p>
                <div class=" -mt-14 px-8 ">
                    <button
                        class="rounded-lg px-4 py-2 bg-red-500 text-gray-100 hover:bg-red-500 duration-300 text-sm max-sm:px-2 ">Show
                        Now <i class="fa-solid fa-arrow-right px-1 py-1  font-bold"></i></button>
                </div>
            </div>
          <div class="relative  max-xl:flex-wrap max-xl: mt-4    max-sm:w-full w-4/12 max-lg:float-left max-xl:w-full">
                <img class="rounded-xl h-60 block  max-sm:w-full w-full" src="@/assets/img/searchimage1.jpg" alt="">
                <div class="absolute inset-0 hover:bg-gray-200 opacity-50 rounded-xl hover:transition-all duration-500">
                </div>
                <p class="absolute -mt-44 px-8 font-bold text-3xl italic text-red-500 max-lg:text-xl w-full">20% OFF</p>
                <p class="absolute -mt-36 px-8  text-3xl italic text-cyan-700 max-lg:text-xl w-full">SUMMRY</p>
                <p class="absolute -mt-28 px-8  text-3xl italic max-lg:text-xl w-full">Product</p>
            </div> 
        </div>
    </div>
</template>

<script>
import card from '@/components/card.vue'
import carousel from 'vue-owl-carousel'

export default {
    name: 'topsellingitemsComp',
    components: {
        card,
        carousel
    },
}
</script>
