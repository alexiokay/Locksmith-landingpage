<template lang="pug">
div(class="w-full md:px-12 flex flex-col text-center space-y-12")
    div(class="flex flex-col ")
        h2(class="text-[4rem] font-bold text-[#02374b]") Locksmith Services
        p(class="text-2xl font-semibold text-[#7c8e98]") Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.
    div(class="flex flex-col lg:flex-row w-full lg:justify-around h-auto items-center justify-center gap-y-12")
        
        div(class="flex flex-col lg:w-1/5 w-3/4 space-y-6 text-[#02374b] lg:text-start items-center lg:items-start")
            nuxt-img(src="icons/car_services.png" width="100" h="30")
            h3(class="font-bold text-4xl") Automotive Services
            p(class="text-xl") Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quo voluptatibus repudiandae dignissimos, omnis distinctio deserunt eum. Accusantium ad neque quos necessitatibus beatae cupiditate, tenetur praesentium provident. Eaque maxime consectetur ad.
            buttonsLearnMore(text="Learn More" class="h-[5rem] w-[17rem] text-xl")
        div(class="flex flex-col lg:w-1/5 w-3/4 space-y-6 text-[#02374b]  lg:text-start items-center lg:items-start")
            nuxt-img(src="icons/commercial_services.png" width="100" h="30")
            h3(class="font-bold text-4xl") Commercial Services
            p(class="text-xl") Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quo voluptatibus repudiandae dignissimos, omnis distinctio deserunt eum. Accusantium ad neque quos necessitatibus beatae cupiditate, tenetur praesentium provident. Eaque maxime consectetur ad.
            buttonsLearnMore(text="Learn More" class="h-[5rem] w-[17rem] text-xl")
        div(class="flex flex-col lg:w-1/5 w-3/4 space-y-6 text-[#02374b]  lg:text-start items-center lg:items-start")
            nuxt-img(src="icons/residental_services.png" width="100" h="30")
            h3(class="font-bold text-4xl") Residential Services
            p(class="text-xl") Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quo voluptatibus repudiandae dignissimos, omnis distinctio deserunt eum. Accusantium ad neque quos necessitatibus beatae cupiditate, tenetur praesentium provident. Eaque maxime consectetur ad.
            buttonsLearnMore(text="Learn More" class="h-[5rem] w-[17rem] text-xl")

</template>

<script setup lang="ts"></script>

<style lang="scss"></style>
