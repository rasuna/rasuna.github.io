<template>
  <div class="container">
    <div>
      <h1>Hi, I'm Rasuna Khatami 👋</h1>

      <p>
        I am a Software Developer at
        <a
          href="https://wearekettle.com"
          target="_blank"
          rel="noopener noreferrer"
          >Kettle</a
        >.
      </p>

      <p>
        You can find my latest projects on
        <a
          href="https://github.com/rasuna"
          target="_blank"
          rel="noopener noreferrer"
          >GitHub</a
        >. I don't post frequently, but you can also follow me on
        <a
          href="https://twitter.com/rasunabaker"
          target="_blank"
          rel="noopener noreferrer"
          >Twitter</a
        >
        and
        <a
          href="http://instagram.com/rasunabaker"
          target="_blank"
          rel="noopener noreferrer"
          >Instagram</a
        >. I'm also on
        <a
          href="https://linkedin.com/in/rasuna"
          target="_blank"
          rel="noopener noreferrer"
          >LinkedIn</a
        >
        if that's your thing.
      </p>

      <p>
        You can reach me via
        <a href="mailto:rasuna.khatami@wearekettle.com">email</a> for any
        business inquiries or at
        <span class="link">rasuna#0023</span>
        on Discord if you want to send me memes and cat pictures.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  head: { title: 'Rasuna Khatami' },
}
</script>

<style lang="scss">
.container {
  display: grid;
  place-items: center;
  margin: 0 auto;
  min-height: 100vh;

  h1 {
    margin: 0;
    font-size: 42px;

    @include breakpoint(xl) {
      font-size: 48px;
    }
  }

  p {
    font-size: 17px;

    @include breakpoint(md) {
      font-size: 19px;
    }

    @include breakpoint(xl) {
      font-size: 21px;
    }
  }

  a,
  .link {
    color: $color-blue;
    text-decoration: none;
  }

  @include breakpoint(md) {
    max-width: 520px;
  }

  @include breakpoint(xl) {
    max-width: 768px;
  }
}
</style>
