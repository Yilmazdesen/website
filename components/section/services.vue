<template>
  <section id="services" class="relative">
    <div class="py-24 sm:py-32">
      <div class="mx-auto w-full px-6 lg:px-8">
        <div class="mx-auto max-w-2xl lg:text-center">
          <h2 class="text-base/7 font-semibold text-blue-600">
            {{ $t('servicesPage.subIndex') }}
          </h2>
          <p class="mt-2 text-pretty text-4xl font-semibold tracking-tight text-gray-900 sm:text-5xl lg:text-balance">
            {{ $t('servicesPage.indexUpperCase') }}
          </p>
          <p class="mt-6 text-lg/8 text-gray-600">
            {{ $t('servicesPage.header') }}
          </p>
        </div>
        <div class="mx-auto mt-16 lg:px-8 w-full sm:mt-20 lg:mt-24 justify-center flex">
          <div class="relative pl-16 max-w-4xl">
            <dt class="text-base/7 font-semibold text-gray-900">
              <div class="absolute left-0 top-0 flex size-10 items-center justify-center rounded-lg bg-blue-600">
                <Icon class="text-3xl text-white" name="simple-icons:traefikmesh" />
              </div>
              {{ $t('servicesPage.title1') }}
            </dt>
            <div class="mt-2 text-base/7 text-gray-600">
              {{ $t('servicesPage.text1') }}
            </div>
          </div>
        </div>
        <div class="mx-auto mt-16 max-w-2xl sm:mt-20 lg:mt-24 lg:max-w-4xl">
          <dl class="grid max-w-xl grid-cols-1 gap-x-8 gap-y-10 lg:max-w-none lg:grid-cols-2 lg:gap-y-16">
            <div class="relative pl-16">
              <dt class="text-base/7 font-semibold text-gray-900">
                <div class="absolute left-0 top-0 flex size-10 items-center justify-center rounded-lg bg-blue-600">
                  <Icon class="text-3xl text-white" name="ant-design:fire-outlined" />
                </div>
                {{ $t('servicesPage.title2') }}
              </dt>
              <div class="mt-2 text-base/7 text-gray-600">
                {{ $t('servicesPage.text2') }}
              </div>
            </div>
            <div class="relative pl-16">
              <dt class="text-base/7 font-semibold text-gray-900">
                <div class="absolute left-0 top-0 flex size-10 items-center justify-center rounded-lg bg-blue-600">
                  <Icon class="text-3xl text-white" name="iconoir:magic-wand" />
                </div>
                {{ $t('servicesPage.title3') }}
              </dt>
              <div class="mt-2 text-base/7 text-gray-600">
                {{ $t('servicesPage.text3') }}
              </div>
            </div>
            <div class="relative pl-16">
              <dt class="text-base/7 font-semibold text-gray-900">
                <div class="absolute left-0 top-0 flex size-10 items-center justify-center rounded-lg bg-blue-600">
                  <Icon class="text-3xl text-white" name="proicons:circle" />
                </div>
                {{ $t('servicesPage.title4') }}
              </dt>
              <div class="mt-2 text-base/7 text-gray-600">
                {{ $t('servicesPage.text4') }}
              </div>
            </div>
            <div class="relative pl-16">
              <dt class="text-base/7 font-semibold text-gray-900">
                <div class="absolute left-0 top-0 flex size-10 items-center justify-center rounded-lg bg-blue-600">
                  <Icon class="text-white text-3xl" name="clarity:truck-line" />
                </div>
                {{ $t('servicesPage.title5') }}
              </dt>
              <div class="mt-2 text-base/7 text-gray-600">
                {{ $t('servicesPage.text5') }}
              </div>
            </div>
          </dl>
        </div>
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
