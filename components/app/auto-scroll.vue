<script setup lang="ts">
const scroll = useState('scroll')
</script>

<template>
  <a href="#home" :class="`${scroll ? 'right-6 bottom-6' : '-right-24 bottom-6'} fixed flex justify-center items-center animation-100 duration-500 delay-400 bg-blue-400 py-2 px-4 rounded-full`">
    <Icon class="-rotate-90 text-3xl" name="weui:arrow-outlined" />
  </a>
</template>
