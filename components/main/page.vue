<script setup lang="ts">
const scroll = useState('scroll', () => false)

function handleScroll(event: Event) {
  const target = event.target as HTMLDivElement | null
  scroll.value = target ? target.scrollTop > 150 : false
}
</script>

<template>
  <div
    class="fixed top-0 left-0 w-screen h-screen overflow-x-hidden overflow-y-auto flex flex-col scroll-smooth
    [&::-webkit-scrollbar]:w-2
  [&::-webkit-scrollbar-track]:bg-gray-100
  [&::-webkit-scrollbar-thumb]:bg-gray-300
  dark:[&::-webkit-scrollbar-track]:bg-transparent
  dark:[&::-webkit-scrollbar-thumb]:bg-blue-400"
    @scroll="handleScroll"
  >
    <slot />
  </div>
</template>
