<template>
  <div>
    <header></header>

    <main>
      <Nuxt />
    </main>

    <footer></footer>
  </div>
</template>

<style lang="scss">
body {
  padding: 0 10vw;
  color: $color-white;
  background-color: $color-black;
  font-family: 'Nunito Sans', -apple-system, BlinkMacSystemFont, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  @include breakpoint(md) {
    padding: 0;
  }
}
</style>
