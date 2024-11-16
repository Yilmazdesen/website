<script setup lang="ts">
const pageTitle = ref('YILMAZ DESEN')
const pageDescription = ref(
  'Yılmaz gravür desen 10 yılı aşkın tecrübe ve hassasiyete sahip tam profesyonel kadrosu ile müşterilerine en yüksek kalitede en uygun fiyatları sunan bir gravür çekim şirketidir. 720m2 kapalı alanı olup Günlük 120 kalıp kapasitesi ile günümüz baskı fabrikalarının her ihtiyacını her saatte karşılaması ve gün içinde teslim etmesi ile ünlü Yılmaz gravür desen 20+ müşterisini günün her saati memnun etmeyi başarmıştır.',
)
const pageKeywords = ref('Sevkiyat, Başlık, Rötuş, Fiske, Mesh Uzunluk ve Kalınlık Raporlama, YILMAZ DESEN')
const pageUrl = ref('https://www.yilmazdesen.com')
const pageImage = ref('/favicon.ico')

useHead({
  title: pageTitle,
  meta: [{
    name: 'description',
    content: pageDescription.value,
  }, {
    name: 'keywords',
    content: pageKeywords.value,
  }, {
    property: 'og:title',
    content: pageTitle.value,
  }, {
    property: 'og:description',
    content: pageDescription.value,
  }, {
    property: 'og:image',
    content: pageImage.value,
  }, {
    property: 'og:url',
    content: pageUrl.value,
  }, {
    property: 'og:type',
    content: 'website',
  }, {
    name: 'twitter:card',
    content: 'summary_large_image',
  }, {
    name: 'twitter:title',
    content: pageTitle.value,
  }, {
    name: 'twitter:description',
    content: pageDescription.value,
  }, {
    name: 'twitter:image',
    content: pageImage.value,
  }],
})
</script>

<template>
  <NuxtLayout>
    <AppHeader />
    <SectionHome />
    <SectionAbout />
    <SectionServices />
    <SectionContact />
    <AppFooter />
    <AppAutoScroll />
  </NuxtLayout>
</template>

<!--

("`-''-/").___..--''"`-._
 `6_ 6  )   `-.  (     ).`-.__.`)
 (_Y_.)'  ._   )  `._ `. ``-..-'
   _..`--'_..-_/  /--'_.'
  ((((.-''  ((((.'  (((.-'

-->
