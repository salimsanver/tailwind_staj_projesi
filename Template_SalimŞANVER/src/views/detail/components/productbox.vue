<template>
    <div class="card ">
        <div class="w-full    mb-20 " >
            <div class="w-full  h  py-4  bg-gray-100  2xl:pt-6    rounded-md ">
                <div class="flex items-center justify-center ">
                    <div class="">
                        <img class=" h-32  " :src="img" alt="">
                    </div>
               <!--@/assets/img/detailimg1.png     Vegetable    Fresh Bread and Pastry Flour 200 g     (34)    $12.68  $14.69 Add-->
            </div>
                <div class=" mt-2 px-4 w-full">
                    <p class="text-xs">{{ title }}</p> <p class="mt-2"> {{ title1 }}</p>
                    <div class="text-xs flex float-left  mt-2 text-yellow-500 w-full ">
                        <i class="fa-sharp fa-solid fa-star "></i>
                        <i class="fa-sharp fa-solid fa-star "></i>
                        <i class="fa-sharp fa-solid fa-star"></i>
                        <i class="fa-sharp fa-solid fa-star"></i>
                 <i class="fa-sharp fa-regular fa-star "></i>
                        <p class="flex float-left  text-cyan-700 mt-0">{{ title2 }}</p>
                    </div>
                    <p class="" >1 Kg</p>
                    <p class="text-green-700  font-bold mt-2">{{ title3 }}<span class="line-through text-black font-normal ">{{ title4 }}</span></p>
                        <div class="w-10/12 ml-4 mt-8 h-10 rounded-3xl bg-gray-200   max-sm:w-full max-sm:-ml-2 ">
                            <div class="bg-slate-500  rounded-2xl w-8 h-8  float-right mt-1 mr-1 max-sm:mr-4 ">
                                <i class="fa-solid fa-plus flex justify-center  pt-2 text-green-700"></i>
                            </div>
                            <p class="px-14 pt-2 max-sm:pl-4 ">{{ title5 }} </p>
                            
                        </div>

                </div>

            </div>

        </div>
    </div>
</template>
<script>

export default {
    name: 'productboxComp',
     
        props:["img","title","title1","title2","title3","title4","title5"],

 
    
}
</script>