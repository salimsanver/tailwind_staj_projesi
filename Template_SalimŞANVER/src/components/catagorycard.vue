<template>
    <div>
        <div class="bg-white   mt-10  justify-between items-center   ">
      <div class="bg-gray-200  w-full h-36  group flex justify-center  pt-10  rounded-xl ">
         <div 
          class="  h-12 w-12   ">
           <img class="mx-auto w-full   " :src="img" alt="">  
         </div>
         <div class="absolute mt-14 ">
            <p class="font-bold ">{{ title }}</p><!--Gown -->
         </div>
         <div :class="img2"
            class=" -mt-10    flex  items-center absolute opacity-0  invisible group-hover:opacity-100 group-hover:block group-hover:visible w-full h-36  bg-cover bg-center rounded-xl">
         </div>
      </div>
      </div>
    </div>
</template>
<script>
export default {
    name: 'catagorycardComponens',
    props:["img","title","img2"]
}
</script>