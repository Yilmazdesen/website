<script setup lang="ts">
const t = useNuxtApp().$i18n.t
const items = computed(() => [
  { label: t('homePage.index'), to: '#home' },
  { label: t('aboutPage.index'), to: '#about' },
  { label: t('servicesPage.index'), to: '#services' },
  { label: t('contactPage.index'), to: '#contact' },
])
const openSlideMenu = ref<boolean>(false)
const scroll = useState('scroll')
const { setLocale, locale } = useI18n()
</script>

<template>
  <header
    :class="`${scroll
      ? 'h-12 bg-white items-bottom shadow'
      : 'lg:h-16 h-20 items-center bg-white/50 hover:bg-white'}
      w-full flex font-medium lg:justify-around justify-between items-center lg:px-2 px-8 z-40 fixed top-0
      animation-all duration-200 delay-100`"
  >
    <div class="h-full flex items-center justify-center gap-4 py-2 lg:w-48">
      <img src="../../assets/logo.png" class="h-full">
      <div
        :class="`${scroll ? 'opacity-100 translate-y-0' : 'opacity-0 -translate-y-5'} flex whitespace-nowrap transition-all duration-300 delay-200 text-lg lg:text-xl font-medium`"
      >
        Yılmaz Desen
      </div>
    </div>
    <button class="flex lg:hidden lg:w-48" @click="openSlideMenu = true">
      <Icon name="uil:bars" class="text-2xl" />
    </button>
    <div class="lg:flex hidden items-center w-5/12 justify-center">
      <a
        v-for="(item, index) in items" :key="index"
        class="cursor-pointer mx-6 hover:mx-8 animation-all text-lg duration-200 hover:scale-110 whitespace-nowrap"
        :href="item.to"
      >
        {{ item.label }}
      </a>
    </div>
    <button
      class="lg:flex hidden"
      @click="() => {
        setLocale(locale === 'tr' ? 'en' : 'tr')
      }"
    >
      <Icon class="text-2xl" name="heroicons:language-solid" />
    </button>
  </header>

  <div
    :class="`fixed ${openSlideMenu ? 'right-0' : '-right-[2000px]'} p-2 flex flex-col justify-between animation-all duration-500 top-0 w-[100%] h-full bg-white z-50`"
  >
    <div class="flex flex-col gap-8">
      <div class="flex justify-between px-2 h-16 border-b items-center">
        <img src="../../assets/logo.png" class="h-full pb-2">
        <button @click="openSlideMenu = false">
          <Icon name="uil:arrow-right" class="text-2xl" />
        </button>
      </div>

      <a
        v-for="(item, index) in items" :key="index" class="border-b cursor-pointer px-4" :href="item.to"
        @click="() => {
          openSlideMenu = false
        }"
      >
        {{ item.label }}
      </a>
      <button
        class="w-full flex border-b items-center justify-between gap-2 px-4"
        @click="() => {
          setLocale(locale === 'tr' ? 'en' : 'tr')
        }"
      >
        <label> {{ $t('changeLanguage') }} </label>
        <Icon class="text-2xl" name="heroicons:language-solid" />
      </button>
    </div>
    <div class="py-2 px-3 text-black justify-center flex">
      <a href="https://github.com/atlasyigitaydin" target="_blank" class="flex items-center gap-2">
        <Icon class="text-xl" name="iconoir:github-circle" />
        <p> made by <ATLAS class="underline"> atlasyigitaydin </ATLAS>  </p>
      </a>
    </div>
  </div>
</template>
