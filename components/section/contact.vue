<template>
  <section id="contact" class="relative flex flex-col w-full items-center gap-16 pt-12">
    <iframe
      class="w-full h-[300px]"
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d190.47498270124956!2d29.08083153452591!3d40.19572063205966!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14ca3e65f7c3896f%3A0x70156ebfd0d8ff07!2sZafer%2C%20Nam%C4%B1k%20Kemal%20Cd.%20No%3A48%20D%3Aa%2C%2016270%20Osmangazi%CC%87%2FBursa!5e0!3m2!1str!2str!4v1731354004012!5m2!1str!2str" loading="lazy" referrerpolicy="no-referrer-when-downgrade"
    />

    <div class="w-full flex flex-col h-full gap-8 lg:justify-around px-8">
      <div class="flex w-full flex-col gap-4">
        <div class="flex flex-wrap-reverse items-center gap-6">
          <label class="lg:text-6xl md:text-4xl text-2xl font-bold"> {{ $t('contactPage.header') }} </label>
          <!-- <Icon name="i-heroicons-phone-solid text-6xl" /> -->
        </div>
        <label class="lg:text-2xl"> {{ $t('contactPage.title') }} </label>
      </div>

      <div class="w-full flex flex-col lg:flex-row gap-12 lg:items-center justify-around">
        <div class="flex flex-col gap-12">
          <div class="flex gap-4 border-b items-start">
            <Icon name="i-heroicons-phone" class="lg:text-3xl text-xl mt-1" />
            <div class="flex flex-col">
              <label class="lg:text-3xl text-lg font-bold"> {{ "0 (542) 531 20 64" }} </label>
              <label class="font-bold text-sm"> {{ "Ramazan YILMAZ" }} </label>
            </div>
          </div>

          <div class="flex gap-4 border-b items-start">
            <Icon name="i-heroicons-phone" class="lg:text-3xl text-xl mt-1" />
            <div class="flex flex-col">
              <label class="lg:text-3xl text-lg font-bold"> {{ "0 (552) 320 49 36" }} </label>
              <label class="font-bold text-sm"> {{ "Atakan YILMAZ" }} </label>
            </div>
          </div>

          <div class="flex gap-4 border-b items-start">
            <Icon name="i-heroicons-phone" class="lg:text-3xl text-xl mt-1" />
            <div class="flex flex-col">
              <label class="lg:text-3xl text-lg font-bold"> {{ "0 (533) 736 83 51" }} </label>
              <label class="font-bold text-sm"> {{ "İsmail YILMAZ" }} </label>
            </div>
          </div>
        </div>

        <div class="flex items-start gap-4">
          <Icon class="text-4xl" name="bx:map" />
          <div class="flex flex-col">
            <label class="font-bold text-xl"> {{ $t('contactPage.address1') }} </label>
            <label class="font-bold text-xl"> {{ $t('contactPage.address2') }} </label>
            <label class="text-xl"> {{ $t('contactPage.address3') }} </label>
            <label class="text-xl"> {{ "no: 48 - 48A" }} </label>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
