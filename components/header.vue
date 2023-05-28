<template lang="pug">
div(class="relative w-full h-[calc(70vh)] flex flex-col gap-y-6 xl:px-[12rem] lg:px-[8rem]  md:px-6 px-4  justify-center ")
    div(class="w-full flex h-full rounded-r-[9rem] rounded-bl-[9rem] absolute top-0 left-0 bg-[#00374c]")
        div(class="w-1/4 hidden lg:flex")
        div(class=" relative lg:rounded-l-[9rem] rounded-bl-[4rem]  lg:w-3/4 w-full bg-[#00374c] rounded-r-[4rem] overflow-clip")
            nuxt-img(src="images/house.png" format="webp" alt="door" class=" h-full object-cover rounded-bl-[5rem]  " width="2560" height="1440")
            .griadent(class="absolute  top-0 left-0 w-full h-full bg-gradient-to-r from-[#1ea1dd] via-transparent  to-transparent opacity-100 rounded-bl-[4rem] ")
    
    h1(class="xl:text-[3.8rem] lg:text-[3rem]  text-[2rem] text-white  mt-8 z-20 ") Twój Zaufany i sprawdzony
        p(class="xl:text-[3.8rem]  lg:text-[3rem] text-[2rem] font-bold  text-white md:-mt-4 ") Śluzarz w mieście
    div(class="text-2xl z-20 mt-12 ")
        span(class="text-white ") Znajdź 
        span(class="text-[#1ea1dd] font-bold") najlepszego ślusarza 
        span(class="text-white ") w twojej okolicy
   
    div(class="flex flex-row lg:w-2/3 xl:w-1/3 border border-[#1ea1dd] rounded-r-full rounded-bl-full h-[4rem] z-20")
        input(type="text" class="h-full w-[calc(100%-4rem)] rounded-bl-[2rem] px-5 text-lg focus:outline-none" placeholder="Miasto lub kod pocztowy")
        button(class="bg-white rounded-r-full  w-[4rem]") 
            SearchIcon(class="h-[2rem] w-[2rem]")
    div(class="flex flex-col z-20 text-white")
        p 24h Linia Pomocy 123 123 123

</template>

<script setup lang="ts">
import SearchIcon from "~icons/iconamoon/search-light";
</script>

<style lang="scss"></style>
