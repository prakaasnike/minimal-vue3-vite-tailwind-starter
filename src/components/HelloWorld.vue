<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="max-w-xl mx-auto text-center mt-10 space-y-4">
    <h1 class="text-xl md:text-3xl font-bold underline py-6">{{ msg }}</h1>
    <h3 class="text-bold text-2xl">Hello World</h3>
    <div class="block">
      <button
        class="
          inline-flex
          justify-center
          items-center
          space-x-2
          border
          font-semibold
          focus:outline-none
          px-3
          py-2
          leading-6
          rounded
          border-cyan-200
          bg-cyan-200
          text-cyan-700
          hover:text-cyan-700 hover:bg-cyan-300 hover:border-cyan-300
          focus:ring focus:ring-cyan-500 focus:ring-opacity-50
          active:bg-cyan-200 active:border-cyan-200
        "
        type="button"
        @click="count++"
      >
        Count : {{ count }}
      </button>
    </div>
  </div>
</template>

