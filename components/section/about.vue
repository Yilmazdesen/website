<template>
  <section id="about" class="relative">
    <div class="mx-auto lg:mt-0 mt-16 grid max-w-2xl grid-cols-1 items-center gap-x-8 gap-y-16 px-4 py-24 sm:px-6 sm:py-20 lg:max-w-7xl lg:grid-cols-2 lg:px-8">
      <div>
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
          {{ $t('aboutPage.index') }}
        </h2>
        <p class="mt-4 text-gray-500">
          {{ $t('aboutPage.header') }}
        </p>

        <dl class="mt-16 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8">
          <div class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">
              {{ $t('aboutPage.title1') }}
            </dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ $t('aboutPage.text1') }}
            </dd>
          </div>
          <div class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">
              {{ $t('aboutPage.title2') }}
            </dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ $t('aboutPage.text2') }}
            </dd>
          </div>
          <div class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">
              {{ $t('aboutPage.title3') }}
            </dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ $t('aboutPage.text3') }}
            </dd>
          </div>
          <div class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">
              {{ $t('aboutPage.title4') }}
            </dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ $t('aboutPage.text4') }}
            </dd>
          </div>
          <div class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">
              {{ $t('aboutPage.title5') }}
            </dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ $t('aboutPage.text5') }}
            </dd>
          </div>
          <div class="border-t border-gray-200 pt-4">
            <dt class="font-medium text-gray-900">
              {{ $t('aboutPage.title6') }}
            </dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ $t('aboutPage.text6') }}
            </dd>
          </div>
        </dl>
      </div>
      <div class="grid grid-cols-2 grid-rows-2 gap-4 sm:gap-6 lg:gap-8">
        <img src="../../assets/service1.jpeg" class="shadow-lg rounded-lg bg-gray-100 my-6">
        <img src="../../assets/service2.jpg" class="shadow-lg rounded-lg bg-gray-100">
        <img src="../../assets/service3.jpg" class="shadow-lg rounded-lg my-4 bg-gray-100">
        <img src="../../assets/service4.jpg" class="shadow-lg rounded-lg bg-gray-100">
      </div>
    </div>
    <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80" aria-hidden="true">
      <div
        class="relative aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-blue-200 to-blue-300 opacity-30 sm:left-[calc(50%-30rem)] sm:w-[122.1875rem]"
        style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"
      />
    </div>
  </section>
</template>
