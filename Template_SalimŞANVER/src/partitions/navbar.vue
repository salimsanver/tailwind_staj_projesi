<template>
    <div class="opacity-100   ">
        <navbarTop />
        <nav class=" w-full flex justify-between">
        <div   class="bg-white    px-24  items-center max-sm:w-full  md:flex md:justify-between max-sm:h-16    w-full ">
            <img class=" w-[11%] mb-8  mt-6 ml-4  max-sm:w-40 max-sm:h-8  max-sm:-ml-12    " src="@/assets/img/navbar2.png" alt="">
            <div class="group hidden max-sm:block ">
  <!-- -mt 20 navbar bak smde-->              <button @click="openBar = !openBar"><i class="fa-solid fa-bars absolute max-sm:left-2 max-sm: text-2xl opacity-0 max-sm:opacity-100  max-sm:-mt-20
                     "></i></button>
                
            </div>
          
               <ul class="text-black w-full   relative z-20 mb-4 flex gap-8 max-sm:w-full  max-sm:absolute  max-xl:hidden
                max-sm:px-4 max-sm:pt-2 max-sm:-mt-12  max-sm:bg-white max-sm:h-screen max-sm:right-0 max-sm:z-50  justify-center" :class="openBar == true ? 'max-sm:block' : 'max-sm:hidden'">
              
                <li  @click="openBar = !openBar" class="max-sm:mt-4  max-sm:h-20 max-sm:px-4 hidden max-sm:block ">Menu <i class="fa-solid fa-xmark max-sm:absolute max-sm:right-10 max-sm:text-2xl max-sm:hover:text-red-500" ></i></li>
                
               <li class=" relative group  max-sm:px-4    "><a href="#">Home</a> <i
                        class="fa-solid text-black fa-chevron-down text-sm max-sm:absolute max-sm:right-6 max-sm:text-lg "></i>
                    <div
                        class=" opacity-0 invisible absolute left-[-40px] bg-white w-[800px] mt-2 rounded-xl hidden  group-hover:opacity-100   group-hover:block group-hover:visible   group-hover:text-blue-900 max-sm:w-80 max-sm:block">
                        <ul class="flex gap-4 text-black   px-8 py-4  max-sm:flex-wrap  ">
                            <li class="hover:border-b-4  duration-300      "><img class="w-[150px] mb-4 max-sm:w-28 "
                                    src="@/assets/img/1.jpg" alt=""><a class="px-6 duration-300    " href="#">Kartshop</a>
                            </li>
                            <li class="hover:border-b-4  duration-300     "><img class="w-[150px] mb-4 max-sm:w-28  "
                                    src="@/assets/img/2.jpg" alt=""><a class="px-6" href="#">Sweetshop</a> </li>
                            <li class="hover:border-b-4  duration-300      "><img class="w-[150px] mb-4 max-sm:w-28"
                                    src="@/assets/img/3.jpg" alt=""><a class="px-6" href="#">Organic</a> </li>
                            <li class="hover:border-b-4   duration-300     "><img class="w-[150px] mb-4 max-sm:w-28"
                                    src="@/assets/img/4.jpg" alt=""><a class="px-6" href="#">Supershop</a> </li>
                            <li class="hover:border-b-4     duration-300   "><img class="w-[150px] mb-4 max-sm:w-28"
                                    src="@/assets/img/5.jpg" alt=""><a class="px-6" href="#">Supershop</a> </li>
                        </ul>
                    </div>

                </li>
       
                <li class="group max-sm:px-4 max-sm:pt-4 2xl:pl-0"><a href="#">Shop</a> <i class="fa-solid text-black fa-chevron-down text-sm max-sm:pt-2 max-sm:absolute max-sm:right-10 max-sm:text-lg"></i>
                    <div
                        class="opacity-0 absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible ">
                        <ul class="text-black">
                            <li class=""><a class="px-6  " href="#">Shop Category Slider</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Shop Category Sidebar</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Shop Banner</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Shop Left Sidebar</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Shop Right Sidebar</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Shop Top Filter</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Shop List</a> </li>
                        </ul>
                    </div>
                </li>
                <li class="group max-sm:pt-4 max-sm:px-4"><a href="#">Product</a> <i class="fa-solid text-black fa-chevron-down text-sm max-sm:absolute max-sm:right-10 max-sm:text-lg"></i>
                    <div
                        class="opacity-0 absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible max-sm:w-60 max-sm:absolute max-sm:left-0">
                        <ul class="text-black">
                            <li class=""><a class="px-6  " href="#">Shop Category Slider</a> </li>
                            <li class="pt-2 group/nav"><a class="px-6" href="#">Shop Category Sidebar</a><i
                                    class="fa-solid fa-chevron-right pr-6"></i>

                                <div
                                    class=" absolute invisible bg-white rounded-xl text-sm  pb-4 pt-2 top-8 py-4 -right-[75%] m hidden group-hover/nav:opacity-100 group-hover/nav:block group-hover/nav:visible max-sm::absolute max-sm:left-0 max-sm:w-44 max-sm:block  ">
                                    <ul class="max-sm:opacity-100 max-sm:block">
                                        <li class="pt-2"><a class="px-6" href="#">Left Thumbnail</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Right Thumbnail</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Bottom Thumbnail</a> </li>
                                    </ul>
                                </div>
                            </li>
                            <li class="pt-2 max-sm:block"><a class="px-6" href="#">Shop Banner</a></li>
                            <li class="pt-2 max-sm:block"><a class="px-6" href="#">Shop Left Sidebar</a> </li>
                            <li class="pt-2 max-sm:block"><a class="px-6" href="#">Shop Right Sidebar</a> </li>
                        </ul>
                    </div>
                </li>

                <li class="group max-sm:pt-4 max-sm:px-4"><a href="#">Mega Menu</a> <i class="fa-solid text-black fa-chevron-down text-sm max-sm:absolute max-sm:right-10 max-sm:text-lg"></i>
                    <div
                        class="opacity-0 absolute invisible justify-between -ml-96 bg-white  rounded-xl text-sm  hidden group-hover:opacity-100 group-hover:block group-hover:visible bg-[url('@/assets/img/bg.png')] bg-cover h-72 w-[800px] max-sm:w-80 max-sm:absolute max-sm:left-0 max-sm:h-full">



                        <div class=" float-left w-[26%] max-sm:float-none max-sm:w-60 ">
                            <h1 class="text-cyan-700     pt-8 pl-6 font-bold ">Daily Vegetables</h1>
                            <ul class="text-black">
                                <li class="pt-2"><a class="px-6" href="#">Beans & Brinjals</a></li>
                                <li class="pt-2"><a class="px-6" href="#">Broccoli & Cauliflower</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Chilies, Garlic</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Vegetables & Salads</a></li>
                                <li class="pt-2"><a class="px-6" href="#">Gourd, Cucumber</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Lettuce & Leafy</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Baby Tender</a></li>

                            </ul>
                        </div>
                        <div class="   float-left w-[26%] max-sm:float-none max-sm:w-60 ">
                            <h1 class="text-cyan-700 pt-8 pl-6 font-bold ">Baby Tender</h1>
                            <ul class="text-black">
                                <li class="pt-2"><a class="px-6" href="#">Beans & Brinjals</a></li>
                                <li class="pt-2"><a class="px-6" href="#">Broccoli & Cauliflower</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Chilies, Garlic</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Vegetables & Salads</a></li>
                                <li class="pt-2"><a class="px-6" href="#">Gourd, Cucumber</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Potatoes & Tomatoes</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Peas & Corn </a></li>
                            </ul>
                        </div>
                        <div class="   float-left w-[26%]  max-sm:float-none max-sm:w-60">
                            <h1 class="text-cyan-700 pt-8 pl-6 font-bold   ">Exotic Vegetables</h1>
                            <ul class="text-black">
                                <li class="pt-2"><a class="px-6" href="#">Asparagus & Artichokes</a></li>
                                <li class="pt-2"><a class="px-6" href="#">Avocados & Peppers</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Broccoli & Zucchini</a> </li>
                                <li class="pt-2"><a class="px-6" href="#">Celery, Fennel & Leeks</a></li>
                                <li class="pt-2"><a class="px-6" href="#">Chilies & Lime</a> </li>
                            </ul>
                        </div>
                    </div>
                </li>
                <li class="group max-sm:pt-4 max-sm:px-4"><a href="#">Blog</a> <i class="fa-solid text-black fa-chevron-down  text-sm  max-sm:absolute max-sm:right-10 max-sm:text-lg"></i>


                    <div
                        class="opacity-0 absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible w-[15%] max-sm:w-60">
                        <ul class="text-black">
                            <li class=""><a class="px-6  " href="#">Blog Detail</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Blog Grid</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Blog List</a> </li>
                        </ul>
                    </div>
                </li>

                <li class="group max-sm:pt-4 max-sm:px-4"><a href="#">Pages</a> <i
                        class="fa-solid text-black fa-chevron-down hover:text-blue-900 text-sm max-sm:absolute max-sm:right-10 max-sm:text-lg"></i>
                    <div
                        class="opacity-0 absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible w-[22%] max-sm:w-60 max-sm:absolute max-sm:left-0">
                        <ul class="text-black">
                            <li class="group/nav"><a class="px-6  " href="#">Email Template <i
                                        class="fa-solid fa-bolt-lightning  text-cyan-700 "></i></a> <i
                                    class="fa-solid fa-chevron-right pl-4"></i>
                                <div
                                    class=" absolute invisible bg-white rounded-xl text-sm  pb-4 pt-2 top-0 py-4 -right-[76%] hidden group-hover/nav:opacity-100 group-hover/nav:block group-hover/nav:visible max-sm::absolute max-sm:left-0 max-sm:w-44 max-sm:block">
                                    <ul>
                                        <li class="pt-2"><a class="px-6" href="#"> Abandonment</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Offer Template</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Order Success</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Reset Password</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Welcome template</a> </li>
                                    </ul>
                                </div>
                            </li>
                            <li class="pt-2 group/nav"><a class="px-6" href="#">Invoice Template <i
                                        class="fa-solid fa-bolt-lightning text-cyan-700 "></i></a><i
                                    class="fa-solid fa-chevron-right pl-3 "></i>

                                <div
                                    class=" absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-2 top-12 py-4 -right-[76%] hidden group-hover/nav:opacity-100 group-hover/nav:block group-hover/nav:visible w-[165px] max-sm::absolute max-sm:left-0 max-sm:w-44 max-sm:block">
                                    <ul>
                                        <li class="pt-2"><a class="px-6" href="#">Invoice 1</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Invoice 2</a> </li>
                                        <li class="pt-2"><a class="px-6" href="#">Invoice 3</a> </li>
                                    </ul>
                                </div>
                            </li>
                            <li class="pt-2"><a class="px-6" href="#">404</a></li>
                            <li class="pt-2"><a class="px-6" href="#">About Us</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Cart</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Contact</a></li>
                            <li class="pt-2"><a class="px-6" href="#">Checkout</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Coming Soon</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Compare</a></li>
                            <li class="pt-2"><a class="px-6" href="#">Faq</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Order Success</a> </li>

                            <li class="pt-2"><a class="px-6" href="#">Order Tracking</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">OTP</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Search</a></li>
                            <li class="pt-2"><a class="px-6" href="#">User Dashboard</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Wishlist</a> </li>
                        </ul>
                    </div>
                </li>

                <li class="group max-sm:pt-4 max-sm:px-4"><a href="#">Seller</a> <i class="fa-solid text-black text-sm  fa-chevron-down  max-sm:absolute max-sm:right-10 max-sm:text-lg "></i>
                    <div
                        class="opacity-0 absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible">
                        <ul class="text-black">
                            <li class=""><a class="px-6  " href="#">Become a Seller</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Seller Dashboard</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Seller Detail</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Seller Detail 2</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Seller Grid</a> </li>
                            <li class="pt-2"><a class="px-6" href="#">Seller Grid 2</a> </li>
                        </ul>
                    </div>
                </li>
            </ul>
         


            <div>
                <div>
                   <!-- -mt 20 navbar bak smde-->      <ul class="flex pl-36 gap-8 text-xl  -mt-14 md:-mt-4 ">
                        <li><i class="fa-sharp fa-regular fa-bookmark  max-sm:hidden "></i></li>
                        <li class="group"> <i class="fa-solid fa-cart-shopping max-sm:hidden"></i>
                            <ul
                                class="opacity-0 absolute invisible group-hover:opacity-100 group-hover:block group-hover:visible">
                                <div class="bg-white w-80 flex h-96 pt-8 -ml-[300px] rounded-xl">
                                    <img class="w-24 h-20 pl-4 " src="@/assets/img/un.png" alt="">
                                    <div class="">
                                        <p class="text-blue-900 text-lg ">Fantasy Crunchy Choco...</p>
                                        <p class="text-black pt-1 "> 1 x$80.58</p>
                                        <div>
                                            <div class="  flex mt-12 -ml-24 w-64 ">
                                                <img class="w-24 h-20 pl-4 " src="@/assets/img/un.png" alt="">
                                                <div>
                                                    <p class="text-blue-900 text-lg w-72 ">Fantasy Crunchy Choco...</p>
                                                    <p class="text-black pt-1"> 1 x$80.58</p>
                                                </div>
                                            </div>
                                            <div class="  flex mt-6 -ml-24 h-24 border-t">
                                                <div class="float-left mt-4 ">
                                                    <p class="ml-8 float-left">Total :</p>
                                                    <p class="float-left ml-40 text-cyan-700">$106.58</p>
                                                </div>
                                                <div class="  mt-14 -ml-64   ">
                                                    <button
                                                        class="rounded-lg px-4 py-2 border-2 border-cyan-700 text-cyan-700 hover:text-white hover:cyan-700 duration-300 hover:bg-cyan-700">View
                                                        Cart</button>

                                                    <button
                                                        class="rounded-lg px-4 py-2 bg-cyan-700 text-white   absolute right-4 ">Checkout</button>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </ul>
                        </li>
                        <li  class="group max-sm:hidden"> <i class="fa-regular fa-user" ></i>
                            <div
                                class="-ml-32 opacity-0 absolute invisible bg-white  rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible  ">
                                <ul class="text-black">


                                    <li class="pt-2 hover:border-b-4     duration-300"><a class="px-6  " href="#"> Log
                                            In</a> </li>
                                    <li class="pt-2 hover:border-b-4     duration-300"><a class="px-6" href="#">Register</a>
                                    </li>
                                    <li class="pt-2 hover:border-b-4     duration-300"><a class="px-6" href="#">Forgot
                                            Password</a> </li>
                                </ul>
                            </div>
                        </li>
                    </ul>
                </div>
            
        
           
                <li class="group max-sm:absolute  hidden max-sm:block max-sm:right-8 max-sm:text-xl max-sm:px-2 max-sm:-mt-6"> <i class="fa-regular fa-user" ></i>
                            <div
                                class="right-0  opacity-0 absolute invisible bg-white  w-40 rounded-xl text-sm  pb-4 pt-4 py-4 hidden group-hover:opacity-100 group-hover:block group-hover:visible ">
                                <ul class="text-black">


                                    <li class="pt-2 hover:border-b-4     duration-300 "><a class="px-6  " href="#"> Log
                                            In</a> </li>
                                    <li class="pt-2 hover:border-b-4     duration-300  "><a class="px-6" href="#">Register</a>
                                    </li>
                                    <li class="pt-2 hover:border-b-4     duration-300  "><a class="px-6" href="#">Forgot
                                            Password</a> </li>
                                </ul>
                            </div>
                        </li>
                    </div>
          
                
        </div>
    </nav>
    </div>
</template>

<script>
import navbarTop from "./components/navbarTop.vue";
export default {

    name: 'navbarComp',
    components: {
        navbarTop
    },
    data() {
        return {
            showLanguage: false, showLanguage1: false,
            openBar:false

        }
    },
    created(){
        window.addEventListener("scroll", function() {
    var navbar = document.querySelector("nav");
    if (window.scrollY > 40) { // sayfa 200px kaydırıldığında navbar sabitlenir
      navbar.classList.add("fixed", "top-0", "z-50" );
    } else {
      navbar.classList.remove("fixed", "top-0", "z-50");
    }
  })
    }
 
}

</script>
<style></style>