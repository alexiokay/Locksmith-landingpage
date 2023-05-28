<template lang="pug">
div(class="nav flex w-full h-[6rem] pl-12 my-6")
    div(class="flex w-1/4 items-center justify-start min-w-[14rem]")
        nuxt-img(class="" alt="logo2"  src="/images/logo2.png" class="w-auto h-full" format="webp")
        nuxt-img(src="/images/text-removebg-preview.png" alt="logo-tekst" class="w-auto h-full" format="webp")
    div#navigation(class="flex w-full justify-end items-center space-x-12 pr-[5rem] text-[#7c8e98] text-3xl mr-[18rem]")
        NuxtLink(class="nav-link" to="/services") Services
        NuxtLink(class="nav-link" to="/about") Locations
        NuxtLink(class="nav-link" to="/contact") Blog
        NuxtLink(class="nav-link" to="/contact") About
        NuxtLink(class="nav-link" to="/contact") Contact
        NuxtLink(class="nav-link" to="/contact") Careers
        button#your-zip-code(class="btn btn-primary  border-[#1ea1dd] w-auto h-3/4 rounded-r-full rounded-bl-full py-2 px-6 border-4 font-semibold text-xl text-[#24a6da]") Your Zip Code

    div(class="absolute top-0 mt-6 right-0 rounded-tl-[2rem] text-xl rounded-b-[2rem] flex px-6 h-[20rem] p-3 w-auto items-start justify-center  bg-[#F2f6f7]  ")

        smallPhone(class="w-[2rem] mt-4")




</template>

<script setup lang="ts"></script>

<style lang="scss"></style>
