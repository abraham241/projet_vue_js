<script setup>
import Navbar from './components/Navbar.vue';
import card from './components/card.vue';
import card_tow from './components/card_tow.vue';
import { MdOutlineFileDownload } from "react-icons/md";

</script>

<template>
   <Navbar/>

   <!-- section hero -->
    <div class="flex-col-reverse flex justify-between md:flex-row lg:flex-row xl:flex-row  py-10 px-20">
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
   <div class="bg-gray-200 py-10 px-20">
        <div class="flex-col  flex justify-between md:flex-row">
            <img src="./assets/image/logo-1.png" alt="">
            <img src="./assets/image/logo-2.png" alt="">
            <img src="./assets/image/logo-3.png" alt="">
            <img src="./assets/image/logo-5.png" alt="">
            <!-- <img src="./assets/image/logo-6.png" alt=""> -->
        </div>
   </div>
   <!-- section des logos  -->

   <!-- section de skills -->
   <div class="flex-col  flex justify-between md:flex-row md:text-left lg:flex-row xl:flex-row 2xl:flex-row py-10 px-20">
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

       <div class="flex gap-10 py-5 ">
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
    <div class="text-center py-10 px-20">
        <h4 class="font-bold text-2xl text-blue-600">
            Services
        </h4>
        <h1 class="text-4xl font-bold py-5">
            Exploring My Design <span class="text-blue-600">Skills</span>
        </h1>
        <p>
            We transform your ideas into a distinctive web project that both inspires <br> you and captivates your customers
        </p>
    </div>
    <!-- les buton du slider -->
    <div class="flex justify-end items-center align-cent gap-3 py-10 px-20 ">
        <div class="h-7 w-7 rounded-full bg-blue-600"></div>
        <div class="h-7 w-7 rounded-full bg-blue-600"></div>
    </div>

    <div class="py-10 px-20">
        <div class="flex-col gap-5 flex justify-between md:flex-row ">
            <card/>
            <card_tow/>
            <card_tow/>
        </div>
    </div>
   <!-- dection des services -->

   <!-- section Our Milestones -->
   <div class="bg-blue-600 text-center py-10 px-20">
        <div>
            <h4 class="font-bold text-2xl text-white">
                Our Milestones
            </h4>
            <h1 class="text-4xl text-white font-bold py-5">
                What sets our studio apart <br> for your projects?
            </h1>
        </div>

        <div class=" flex-col gap-4 flex justify-between md:flex-row lg:flex-row xl:flex-row 2xl:flex-row">
            <div class="w-full bg-white md:w-56 p-5 rounded">
                <h1 class="font-bold  text-3xl">8000+</h1>
                <p>
                    Figma ipsum component <br> variant main layer. Hand.
                </p>
            </div>
            <div class="w-full bg-white md:w-56 p-5 rounded">
                <h1 class="font-bold  text-3xl">100%</h1>
                <p>
                    Figma ipsum component <br> variant main layer. Hand.
                </p>
            </div>
            <div class="w-full bg-white md:w-56 p-5 rounded">
                <h1 class="font-bold  text-3xl">3.5K</h1>
                <p>
                    Figma ipsum component <br> variant main layer. Hand.
                </p>
            </div>
            <div class="w-full bg-white md:w-56 p-5 rounded">
                <h1 class="font-bold  text-3xl">240+</h1>
                <p>
                    Figma ipsum component <br> variant main layer. Hand.
                </p>
            </div>
        </div>
   </div>
   <!-- section Our Milestones -->

   <!-- section portfolio -->
   <div class="py-10 px-20"> 
        <div class="text-center">
            <h4 class="font-bold text-2xl text-blue-600">
                Our projects
            </h4>
            <h1 class="text-4xl font-bold py-5">
                Presenting My Design <br> Portfolio and Case Studies
            </h1>
        </div>
        <div class="flex-col gap-3 flex  md:flex-row  md:justify-center  items-center justify-center">
            <div class="flex gap-2">
                <button class="h-10 bg-blue-600 text-white font-bold  rounded-full w-32">All</button>
                <button class="h-10 border-2 border-blue-600 text-bleu-600 font-bold  rounded-full w-32">UI/UX Design</button>
            </div>
            <div class="flex gap-2">
                <button class="h-10 border-2 border-blue-600 text-bleu-600 font-bold  rounded-full w-44">Branding Design</button>
                <button class="h-10 border-2 border-blue-600 text-bleu-600 font-bold  rounded-full w-32">Wordpress</button>
            </div>
        </div>
        <div class="">
            <div class="flex-col gap-2 flex justify-between md:flex-row lg:flex-row xl:flex-row py-10  ">
                <img src="./assets/image/preview2.png" alt="" style="height: 396px; height: 356px;">
                <img src="./assets/image/preview1.png" alt="" style="height: 396px; height: 356px;">
                <img src="./assets/image/preview3.png" alt="" style="height: 396px; height: 356px;">
            </div> 
            <div class="flex-col gap-2 flex justify-between md:flex-row lg:flex-row xl:flex-row ">
                <img src="./assets/image/preview4.png" style="height: 396px; height: 356px;">
                <img src="./assets/image/preview5.png" style="height: 396px; height: 356px;">
                <img src="./assets/image/preview6.png" style="height: 396px; height: 356px;">
            </div>
        </div>
   </div>
   <!-- section portfolio -->
<!-- ============================================================================== -->
   <!-- section temoignage  -->
    <div class="py-10 px-20">
        <div>
            <div class="text-center">
                <h4 class="font-bold text-2xl text-blue-600">
                    Testimonials
                </h4>
                <h1 class="text-4xl  font-bold py-5">
                    The Trust From Clients
                </h1>
            </div>  
        </div>
        <div class="flex justify-center gap-5 py-7">
            <div class="h-7 w-7 rounded-full bg-blue-600"></div>
            <div class="h-7 w-7 rounded-full bg-blue-600"></div>
        </div>
        <div class="">
            <div class="sm:overflow-x-scroll gap-5 flex justify-between md:flex-row lg:flex-row xl:flex-row 2xl:flex-row ">
                <div class=" md:w-72 border border-gray-200 p-7 rounded">
                    <div class="flex justify-center items-center">
                        <img class="" src="./assets/image/Ellipse 3.png" alt="">
                    </div>
                    <div class="flex justify-center items-center text-yellow-400 pt-2">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <p class="py-3">
                        Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet tellus eget egestas. Enim ultrices dictumst tortor in eget neque vestibulum potenti tempus
                    </p>
                    <div class="text-center">
                        <h4 class="font-bold">
                        Savannah Nguyen
                        </h4>
                        <p>President of Sales</p>
                    </div>
                </div>
                <div class=" w-72 border border-gray-200 p-7 rounded">
                    <div class="flex justify-center items-center">
                        <img class="" src="./assets/image/Ellipse 3.png" alt="">
                    </div>
                    <div class="flex justify-center items-center text-yellow-400 pt-2">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <p class="py-3">
                        Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet tellus eget egestas. Enim ultrices dictumst tortor in eget neque vestibulum potenti tempus
                    </p>
                    <div class="text-center">
                        <h4 class="font-bold">
                        Savannah Nguyen
                        </h4>
                        <p>President of Sales</p>
                    </div>
                </div>
                <div class=" w-72 border border-gray-200 p-7 rounded">
                    <div class="flex justify-center items-center">
                        <img class="" src="./assets/image/Ellipse 3.png" alt="">
                    </div>
                    <div class="flex justify-center items-center text-yellow-400 pt-2">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <p class="py-3">
                        Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet tellus eget egestas. Enim ultrices dictumst tortor in eget neque vestibulum potenti tempus
                    </p>
                    <div class="text-center">
                        <h4 class="font-bold">
                        Savannah Nguyen
                        </h4>
                        <p>President of Sales</p>
                    </div>
                </div>
                <div class=" w-72 border border-gray-200 p-7 rounded">
                    <div class="flex justify-center items-center">
                        <img class="" src="./assets/image/Ellipse 3.png" alt="">
                    </div>
                    <div class="flex justify-center items-center text-yellow-400 pt-2">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                            <path fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <p class="py-3">
                        Lorem ipsum dolor sit amet consectetur. Nibh porttitor aliquet tellus eget egestas. Enim ultrices dictumst tortor in eget neque vestibulum potenti tempus
                    </p>
                    <div class="text-center">
                        <h4 class="font-bold">
                        Savannah Nguyen
                        </h4>
                        <p>President of Sales</p>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
   <!-- section temoignage  -->

   <!-- section contact -->
   <div class="bg-blue-600">
        <div class="text-center"> 
            <h4 class="text-2xl text-white">
                contact me
            </h4>
            <h1 class="text-4xl text-white font-bold ">
                Request Free Consultancy
            </h1>
        </div>
        <div class="flex-col  flex justify-center items-center gap-7 py-10 md:flex-row lg:flex-row xl:flex-row 2xl:flex-row">
            <div class="bg-white  md:w-1/3  rounded p-4">
                <div class="pb-7">
                    <p class="font-bold">Hotline 24/7</p>
                    <p class="text-xl font-bold">(+23) 5535 68 68</p>
                </div>
                <div>
                    <p><span class="font-bold">Address:</span>2972 Westheimer Rd. Santa Ana, Illinois 85486</p>
                    <p><span class="font-bold">Email:</span>nevaeh.simmons@example.com</p>
                    <p><span class="font-bold">Fax:</span>(702) 555-0122</p>
                    <p><span class="font-bold">Work Hour:</span>Mon - Sat: 9:00 - 18:00</p>
                </div>
            </div>
            <div class="pt-10">
                <div class="">
                    <div class="flex  gap-3">
                        <input type="text" class="w-full  h-10" name="" id="" placeholder="Name*">
                        <input type="text" class="w-full  h-10" name="" id="" placeholder="Email Address*">
                    </div>
                    <div class="py-2 ">
                        <input type="text" class="w-full h-10" name="" id="" placeholder="How can we help you?">
                    </div>
                    <div class="flex">
                        <input type="text" class="w-full h-20" name="" id="" placeholder="How can we help you?">
                    </div>
                </div>
                <div>
                    <div class="flex gap-6 text-xs p-2">     
                        <input type="checkbox"  class="form-checkbox h-5 w-5 text-indigo-600">
                        <p>By submitting, i’m agreed to the Terms & Conditons</p>
                    </div>
                    <div>
                        <button class="h-10  border-white text-white bg-blue-900 font-bold  rounded-full w-44">Request Now</button>
                    </div>
                </div>
            </div>
        </div>
   </div>
   <!-- section contact -->

   <!-- footer -->
   <div class="bg-blue-600 py-10 px-20 sm:text-center">
        <div class="flex-col flex  justify-center items-center  md:flex-row lg:flex-row xl:flex-row 2xl:flex-row">
            <div class="flex ">
                <img src="./assets/image/Group 8.png" alt="">
                <h1 class="pt-3 font-bold">AeroVision</h1>
            </div>
            <div>
                <p>© Copyright 2023. All Rights Reserved</p>
            </div>
            <div class="flex">
                <p>FOLLOW US:</p>
            
            </div>
        </div> 
    </div>
   <!-- footer -->
</template>



<style scoped>

</style>
