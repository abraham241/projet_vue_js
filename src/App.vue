<script setup>
import Navbar from './components/Navbar.vue';
import { MdOutlineFileDownload } from "react-icons/md";

</script>

<template>
   <Navbar/>

   <!-- section hero -->
    <div class="flex-col-reverse flex justify-between md:flex-row lg:flex-row 2xl:flex-row  py-10 px-20">
        <div class="pt-20 ">
            <p class="font-bold">Welcome to my Portfolio</p>
            <h1 class="text-6xl font-bold py-5">
                Hi I’m <br>
                <span class="text-blue-600">Robert Junior</span> <br>
                Product Designer
            </h1>
            <p>
                Collaborating with highly skilled individuals, <br>
                our agency delivers top-quality services
            </p>

            <div class="flex gap-10 py-5">
                <button class=" h-12 bg-blue-600 text-white font-bold  rounded-full w-32">
                    Let’s chat
                </button>
                <button class=" h-12 border-2 border-blue-600 text-bleu-600 font-bold  rounded-full w-32">
                    Download CV
                </button>
                <!-- <font-awesome-icon icon="fa-solid fa-user-secret" /> -->
            </div>
        </div>
        <div>
            <img src="./assets/image/pexels-wictor-cardoso-18269632-removebg 1.png" alt="">
        </div>
    </div>
   <!-- section hero -->

   <!-- section des logos  -->
   <div class="bg-gray-200">
        <div class="flex-col flex justify-between md:flex-row xl:flex-row py-10 px-20">
            <img src="./assets/image/logo-1.png" alt="">
            <img src="./assets/image/logo-2.png" alt="">
            <img src="./assets/image/logo-3.png" alt="">
            <img src="./assets/image/logo-4.png" alt="">
            <img src="./assets/image/logo-5.png" alt="">
        </div>
   </div>
   <!-- section des logos  -->

   <!-- section de skills -->
   <div class="flex-col  flex justify-between md:flex-row md:text-left lg:flex-row xl:flex-row 2xl:flex row py-10 px-20">
       <div class="pt-5">
            <img src="./assets/image/pexel2.png" alt="" class="h-[500px]">
       </div>
       

       <div>
        <div>
            <div class="py-5 text-center">
                <span class="text-blue-600 font-bold">About Me</span>
                <h1 class="text-4xl font-bold py-5">
                    <span class="text-blue-600 font-bold text-4xl">20 Year’s Experience</span> <br>
                    on Product Design
                </h1>
                <p>
                    Hello there! I'm Robert Junior. I specialize in web design and <br> development, and 
                    I'm deeply passionate and committed to my craft. <br>
                    With 20 years of experience as a professional graphic designe
                </p>
            </div>

       <div class="flex gap-10 py-5">
            <button class="h-10 bg-blue-600 text-white font-bold  rounded-full w-32">Main Skills</button>
            <button class="h-10 border-2 border-blue-600 text-bleu-600 font-bold  rounded-full w-32">Awards</button>
            <button class="h-10 border-2 border-blue-600 text-bleu-600 font-bold  rounded-full w-32">Education</button>
       </div>
            <div>
                <h1 class="font-bold py-2">User Experience Design - UI/UX</h1>
                <div class="bg-gray-200 w-[500px] h-4 rounded-full">
                    <div class="bg-blue-600 w-[470px] h-4 rounded-full text-white font-bold flex  gap-5">
                        
                    </div>
                </div>
            </div>
            <div>
                <h1 class="font-bold py-2">Web & User Interface Design - Development</h1>
                <div class="bg-gray-200 w-[500px] h-4 rounded-full">
                    <div class="bg-blue-600 w-[470px] h-4 rounded-full text-white font-bold flex  gap-5">
                        
                    </div>
                </div>
            </div>
            <div>
                <h1 class="font-bold py-2">Interaction Design - Animation</h1>
                <div class="bg-gray-200 w-[500px] h-4 rounded-full">
                    <div class="bg-blue-600 w-[470px] h-4 rounded-full text-white font-bold flex  gap-5">
                        
                    </div>
                </div>
            </div>
       </div>
       </div>
       
</div>
   <!-- section de skills -->

   <!-- dection des services -->
    <div>
        <h4>
            Services
        </h4>
        <h1>
            Exploring My Design <span>Skills</span>
        </h1>
        <p>
            We transform your ideas into a distinctive web project that both inspires <br> you and captivates your customers
        </p>
    </div>
   <!-- dection des services -->
</template>



<style scoped>

</style>
