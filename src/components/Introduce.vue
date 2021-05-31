<template lang='pug'>
//- Declaration
mixin link-btn(name)
  .h-8.bg-gray-500.flex.items-center.justify-center.px-4.font-black.text-white= name
//- html
header.flex.flex-col.p-5(
  v-once
  class="w-full bg-[#222] overflow-y-auto flex-shrink-0"
  class="sm:w-[260px]"
)

  h1.text-gray-300.text-4xl.font-mono.pb-2.font-black H1R0YUK1#[br]54W4N0
  label.text-gray-400.text-l.text-right.bg-gray-700.px-2.py-1.tracking-widest 澤野弘之

  blockquote.text-gray-500.text-xs.mt-2.mb-8.text-justify.
    Lorem ipsum dolor sit amet consectetur adipiscing elit blandit purus varius leo risus,
    facilisi orci per gravida auctor senectus nec duis laoreet consequat montes,
    cubilia volutpat integer libero sociosqu felis dui phasellus congue rutrum augue.
    Eleifend nunc orci eros consectetur conubia molestie dolor fames,
    purus litora interdum metus dis condimentum nec,
    libero placerat gravida aliquet natoque inceptos blandit.

  .w-full.mt-auto.flex.flex-row.justify-between.items-center.flex-wrap.gap-4.my-2
    +link-btn('Twitter')
    +link-btn('Facebook')
    +link-btn('YouTube')
    +link-btn('Wiki')
  footer.w-full.text-xs.text-gray-300.mt-2
    a.text-blue-400.p-1.transition-shadow(
      class="hover:ring-2 focus:ring-2 focus:outline-none"
      class="active:ring-4"
      href="https://hikarintu.github.io/homepage/"
      rel="noopener"
      target="blank"
      title="Personal Homepage"
    ) HikariNTU
    |@ 2021
</template>

<script setup>

</script>