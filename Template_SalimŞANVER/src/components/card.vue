<template>
    <div class="card">
        
        <div class="w-full ">
                <div :class="img"
                    class=" w-full h-72   max-sm:px-20  bg-cover bg-center rounded-xl group  max-sm:h-48  ">
                    <div class="w-full  h-10 max-sm:ml-20">

             
                    <div class="bg-white w-8 h-8   float-right mt-3 mr-3  rounded-lg flex justify-center items-center group  max-xl:-ml-40" >
                        <i class="fa-sharp fa-regular fa-bookmark     text-cyan-700 hover:text-blue-800"></i>
                        
                    </div>
                </div>
                    <div class="opacity-0 invisible  group-hover:opacity-100   group-hover:block group-hover:visible   w-full h-10 mt-44 max-sm:-ml-16 max-sm:-mt-2">
                        <div
                            class=" bg-white w-40 h-10     rounded-lg flex justify-center items-center gap-8  mx-auto max-sm:mt-28  max-sm:left-23 max-sm:w-32   ">
                            <i class="fa-regular fa-eye text-cyan-700 hover:text-blue-800"></i>
                            <i class="fa-solid fa-arrows-rotate text-cyan-700 hover:text-blue-800"></i>
                            <i class="fa-regular fa-heart text-cyan-700 hover:text-red-800"></i>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="bg-white text-center  ">
                            <router-link to="/detail">
                                <p class="text-sm   font-bold px-1 mt-2">{{ title }}</p>
                            </router-link>
                        <p class="px-6 text-cyan-700 mt-1">${{ newPrince }} <span class="line-through text-black">{{ prince }}</span></p>
                    </div>
                </div>
            </div>
    </div>
    <!-- 
        Brown Khadi Jacket
        $26.69
        28.56
    -->
</template>
  
<script>
export default {
    name: 'cardComponens',
    props:["img","title","newPrince","prince"]
}
</script>
  