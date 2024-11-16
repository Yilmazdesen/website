<template>
  <MainPage class="montserrat">
    <slot />
  </MainPage>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Work+Sans:ital@0;1&display=swap');
.montserrat {
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}
</style>
