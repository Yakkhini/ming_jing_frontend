<template>
  <div
    class="font-serif hover:font-sans subpixel-antialiased font-medium hover:font-bold text-5xl tracking-widest text-slate-500 hover:text-indigo-900"
  >
    {{ msg }}
  </div>
</template>

<script>
export default {
  name: "BigTitle",
  props: {
    msg: String,
  },
};
</script>
