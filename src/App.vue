<template>
  <div class="grid 	grid-flow-col grid-cols-3 grid-rows-3 justify-items-center gap-y-3 py-24 bg-slate-300">

    <div class="blur-sm hover:blur-none">
      <img class="object-cover h-36" alt="Vue logo" src="./assets/logo.svg" />
    </div>

    <div>
      <SideBarVue/>
    </div>

    <div>
      <CostomButtonVue/>
    </div>
    
  </div>
</template>

<script setup>
//import BigTitleVue from "./components/BigTitle.vue";
import SideBarVue from "./components/SideBar.vue";
import CostomButtonVue from "./components/CustomButton.vue";
</script>
