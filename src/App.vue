<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="mx-auto items-center justify-center bg-teal-300">
    <div class="h-screen px-10 p-10">
      <div
        class="
          flex
          mx-auto
          justify-center
          h-[15vh]
          items-center
          bg-black
          sticky
          space-x-4
          bg-opacity-90
          backdrop-filter backdrop-blur-lg
          rounded
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
  </div>
</template>

