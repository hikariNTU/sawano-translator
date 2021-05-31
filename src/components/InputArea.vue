<template lang='pug'>
.flex.flex-col.flex-grow.mt-4(class="sm:ml-4")
  h1.text-gray-400.text-2xl.font-thin.mb-2.text-left.tracking-widest Sawano Hiroyuki Translator
  .w-full.text-gray-400.rounded-lg.flex.justify-start.text-7xl.tracking-widest H3LL0 L3T'S ST4RT
  textarea.w-full.mt-4(
    type="text"
    class="focus:outline-none focus:ring-2 ring-gray-700 flex-grow"
    class="bg-[#222] text-[#888] text-3xl p-12 tracking-[0.3em] uppercase resize-none"
    v-model="inputText"
  )/
</template>

<script setup>
import { ref } from "vue"

const inputText = ref('')
;</script>
