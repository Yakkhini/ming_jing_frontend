<template>
  <div class="grid grid-cols-1 justify-items-center gap-y-3 py-24 bg-slate-300">
    <div class="blur-sm hover:blur-none">
      <img alt="Vue logo" src="./assets/logo.svg" />
    </div>
    <div class="opacity-50 hover:opacity-100 drop-shadow-lg">
      <BigTitle msg="明镜" />
    </div>
    <div class="my-20">
      <button
        class="py-3 px-5 bg-blue-700 ring rounded-full font-sans text-slate-100 font-bold text-xl tracking-widest"
      >
        链接账户
      </button>
    </div>
  </div>
</template>

<script>
import BigTitle from "./components/BigTitle.vue";

export default {
  name: "App",
  components: {
    BigTitle,
  },
};
</script>
