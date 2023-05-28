<template lang="pug">
div(class="flex md:flex-row flex-col w-full h-auto py-6 items-center justify-center gap-x-[8rem] gap-y-8 md:gap-y-0 p-8")
    div(class="flex flex-col w-full md:w-2/5 h-full space-y-8")
        h3(class="text-[#02374b] md:text-[4rem]  text-xl font-bold") Why Choose Us
        p(class='text-2xl font-semibold text-[#7c8e98]') Your trusted locksmith in the Greater Toronto Area
        p(class="text-2xl text-[#7c8e98]") Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.
        div(class='flex w-full h-auto text-[#02374b] font-bold gap-x-[5rem] flex-wrap xl:flex-nowrap')
            div(class="flex flex-col h-full space-y-4")
                div(class="flex w-full items-center text-2xl space-x-3")
                    PhoneIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p 20+ Years Experience
                div(class="flex w-full items-center text-2xl space-x-3")
                    TimerIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Open 24 Hours
                div(class="flex w-full items-center text-2xl space-x-3")
                    FastIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Fast Arrival Time
                div(class="flex w-full items-center text-2xl space-x-3")
                    SavingIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Competitive Pricing
            div(class="flex flex-col  h-full space-y-4")
                div(class="flex w-full items-center text-2xl space-x-3")
                    WorldIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Localy owned and operated
                div(class="flex w-full items-center text-2xl space-x-3")
                    CardIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Accepting Credit Cards
                div(class="flex w-full items-center text-2xl space-x-3")
                    AimingIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Quick & Honest Service
                div(class="flex w-full items-center text-2xl space-x-3")
                    SatisfactionIcon(class="w-[4rem] h-[4rem] text-gray-400")
                    p Satisfaction Guaranteed
    div(class="flex flex-col md:flex-row w-full md:w-2/5 flex-wrap gap-y-[1rem] h-full md:rounded-tr-[6rem] md:rounded-b-[6rem]  md:bg-white md:shadow-[0_1px_60px_-15px_rgba(0,0,0,0.1)] md:p-[6rem]  justify-between")
        div(class="w-full md:w-[calc(50%-2rem)] h-auto space-y-4")
            p(class="text-[#27ade5] text-[4rem] font-bold") 1,489+
            hr(class="w-full h-1 border-2 mt-2")
            p(class="text-[#02374b] text-3xl font-bold ") Clients Served
            p(class="text-[#7c8e98] text-xl") dsadsadsa dasd asd asd as dasdas dsa 

        div(class="w-full md:w-[calc(50%-2rem)] h-auto space-y-4")
            p(class="text-[#27ade5] text-[4rem] font-bold") $1.2+
            hr(class="w-full h-1 border-2 mt-2")
            p(class="text-[#02374b] text-3xl font-bold ") Money Saved
            p(class="text-[#7c8e98] text-xl") dsadsadsa dasd asd asd as dasdas dsa 

        div(class="w-full md:w-[calc(50%-2rem)] h-auto space-y-4")
            p(class="text-[#27ade5] text-[4rem] font-bold") 7,543+
            hr(class="w-full h-1 border-2 mt-2")
            p(class="text-[#02374b] text-3xl font-bold ") Projects Completed
            p(class="text-[#7c8e98] text-xl") dsadsadsa dasd asd asd as dasdas dsa 

        div(class="w-full md:w-[calc(50%-2rem)] h-auto space-y-4")
            p(class="text-[#27ade5] text-[4rem] font-bold") 47+
            hr(class="w-full h-1 border-2 mt-2")
            p(class="text-[#02374b] text-3xl font-bold ") Locations Served
            p(class="text-[#7c8e98] text-xl") dsadsadsa dasd asd asd as dasdas dsa 


</template>

<script setup lang="ts">
import TimerIcon from "~icons/ion/timer-outline";
import PhoneIcon from "~icons/mingcute/phone-call-line";
import WorldIcon from "~icons/clarity/world-line";
import CardIcon from "~icons/solar/card-recive-linear";
import AimingIcon from "~icons/ep/aim";
import SatisfactionIcon from "~icons/mdi/user-check-outline";
import SavingIcon from "~icons/fluent/savings-24-regular";
import FastIcon from "~icons/material-symbols/speed-outline";
</script>

<style lang="scss"></style>
