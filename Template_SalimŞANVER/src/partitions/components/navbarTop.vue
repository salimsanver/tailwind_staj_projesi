<template>
  

    <div  class=" bg-cyan-700    flex justify-between   px-24  h-10  max-sm:bg-cyan-700   max-sm:w-full">
        <p class=" float-left text-sm text-white  mt-2 ml-4 max-sm:invisible  max-xl:text-xs   max-xl:hidden" > <i class=" fas fa-map-marker"></i> 1418 Riverwood Drive, CA 96052, US
        </p>
    <span class="  text-white  mt-2 text-sm max-sm:invisible max-sm:hidden md:text-xs  max-lg:hidden">Welcome to Fastkart! Wrap new offers/gift every signle day on Weekends. New Coupon Code...  </span>
   <!-- <span>Something you love is now on sale! </span>-->
 
        <div class="flex w-64   ">
    
    
        <div class="relative flex flex-col items-center center   border-r first-letter: max-sm: ml-20 w-full ">
    
        
            <button @click="showLanguage = !showLanguage ,showLanguage1= false" class="bg-cyan-700 text-white  w-full items-center justify-between   text-sm mt-2 raunded-lg trancking-wider active:border-white duration-300 font-bold  max-sm:w-24">Turki <i class="fa-solid text-white fa-chevron-down px-1 "></i> </button>
     

      
            <ul v-show="showLanguage" class="text-left w-[140px] rounded-lg   bg-white  mt-10 mr-20 fixed z-50 ">
        <li class="px-4 py-1 hover:bg-gray-100 border-b flex"><img class="w-6   pt-1 pr-1" src="@/assets/img/united-kingdom.png" alt="">  English</li>
        <li class="px-4 py-1 hover:bg-gray-100 border-b flex"> <img class="w-6  pt-1 pr-1" src="@/assets/img/germany.png" alt="">Germany</li>
        <li class="px-4 py-1 hover:bg-gray-100 border-b flex"><img class="w-6   pt-1 pr-1" src="@/assets/img/turkey.png" alt="">Turki</li>
    </ul> 

    </div>
    <div class="relative flex flex-col   items-center    center w-full ">
    <button  @click="showLanguage1 = !showLanguage1 , showLanguage = false " class="bg-cyan-700 text-white  w-full items-center justify-between   text-sm p-2 raunded-lg trancking-wider active:border-white duration-300  max-sm:w-24">USD <i class="fa-solid text-white fa-chevron-down  px-1"></i> </button>
    <ul v-show="showLanguage1 " class="text-left w-[70px] rounded-lg bg-white fixed z-50 mt-10 mr-6 ">
    <li class="px-4 py-1 hover:bg-gray-100 border-b flex"> USD</li>
    <li class="px-4 py-1 hover:bg-gray-100 border-b flex ">EUR</li>
    <li class="px-4 py-1 hover:bg-gray-100 border-b flex">CND</li>
    </ul> 
    </div>
    </div>
    
    
    
    
    
    
    </div>
    </template>
    
    <script >
    export default {
        name: 'navbarTop',
        data(){
            return{
                showLanguage:false,showLanguage1:false
    
            }
        }}
        








   


    
    
    </script>
 
    