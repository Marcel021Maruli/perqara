<script setup>
  import Content from "./content.vue";
  import LeftContent from "./left-content.vue"
  import RightContent from "./right-content.vue"
</script>

<template>
  <div class="ProfilePage">
    <div class="w-full flex justify-center mt-5">
      <div
        class="w-full md:w-[1128px] md:flex-row items-center md:items-start flex-col flex justify-center"
      >
      <LeftContent/>
     
        <Content />
        <RightContent />
        </div>
      </div>
    </div>
  </template>
