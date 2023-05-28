<template lang="pug">

button(class="bg-[#1ea1dd] group  text-xl min-w-[12rem]  min-h-[3.3rem] rounded-r-full rounded-bl-full py-2 px-2 flex items-center hover:shadow-[0_2px_30px_-15px_rgba(0,0,0,0.9)] justify-center hover:bg-[#00374c] ") {{text}}
    slot(name="icon")

</template>

<script setup lang="ts">
defineProps({
  text: String,
});
</script>

<style lang="scss"></style>
