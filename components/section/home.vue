<template>
  <section id="home" class="lg:min-h-full">
    <div class="relative isolate bg-white min-h-full flex lg:flex-row flex-col-reverse items-center lg:gap-24 gap-2 justify-around w-full lg:mt-0 mt-[65px] px-0 lg:px-24">
      <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80" aria-hidden="true">
        <div class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-blue-400 to-blue-300 opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
      </div>
      <div class="flex flex-col lg:gap-8 gap-2 lg:px-0 px-6">
        <h2 class="text-balance lg:text-6xl text-xl font-bold text-gray-900">
          {{ $t('BIGBROTHER') }}
        </h2>
        <h1 class="text-balance lg:text-5xl text-xl font-light tracking-tight text-gray-900">
          {{ $t('homePage.header') }}
        </h1>
        <p class="font-thin text-gray-500 text-pretty lg:text-xl">
          {{ $t('homePage.text') }}
        </p>
        <div class="flex lg:flex-row flex-col gap-8 items-center lg:mt-0 mt-4">
          <a href="#services" class="rounded-md bg-blue-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600">  {{ $t('homePage.btnServices') }} </a>
          <a href="#contact" class="text-sm/6 font-semibold text-gray-900">{{ $t('homePage.btnContact') }} <span aria-hidden="true">→</span></a>
        </div>
      </div>
      <video autoplay muted loop playsinline class="lg:w-5/12 w-full lg:rounded-xl shadow-xl"> <source src="../../assets/bg_video.mov" type="video/mp4"> {{ $t('errorVideo') }} </video>
      <div class="absolute inset-x-0 top-[calc(100%-13rem)] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[calc(100%-30rem)]" aria-hidden="true">
        <div class="relative left-[calc(50%+3rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%+36rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
      </div>
    </div>
  </section>
</template>
