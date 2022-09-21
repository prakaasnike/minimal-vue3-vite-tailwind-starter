<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="mx-auto items-center justify-center">
    <div
      class="
        flex
        mx-auto
        justify-center
        h-[40vh]
        items-center
        bg-black
        space-x-4
      "
    >
      <span>
        <a href="https://vitejs.dev" target="_blank">
          <img src="/vite.svg" class="h-16 p-2" alt="Vite logo" /> </a
      ></span>
      <span
        ><a href="https://vuejs.org/" target="_blank">
          <img src="./assets/vue.svg" class="h-16 p-2" alt="Vue logo" /> </a
      ></span>
      <span
        ><a href="https://tailwindcss.org/" target="_blank">
          <img
            src="./assets/tailwindcss.svg"
            class="h-16"
            alt="TailwindCss logo"
          /> </a
      ></span>
    </div>
    <div>
      <HelloWorld msg="Vite + Vue 3 + Tailwindcss" />
    </div>
  </div>
</template>

