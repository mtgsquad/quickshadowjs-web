<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        QuickShadow.JS
      </h1>
      <div class="links">
        <a
          href="https://npmjs.com/package/quickshadow"
          target="_blank"
          rel="noopener noreferrer"
          class="button--white"
        >
          npm
        </a>
        <a
          href="/documentation"
          target="_blank"
          rel="noopener noreferrer"
          class="button--white"
        >
          Documentation
        </a>
        <a
          href="https://github.com/mtgsquad/quickshadow"
          target="_blank"
          rel="noopener noreferrer"
          class="button--white"
        >
          GitHub
        </a>
      </div>
      <br>
      <div class="under">
        <p class="white under2">Made with ❤ by <a href="https://molai.dev">molai.dev</a></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Roboto Mono', monospace;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #ffffff;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #ffffff;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.under {
  position: relative;
}

.under2 {
  position: absolute;
  top: 85%;
  left: 290px;
  transform: translateX(-50, -50);
}
</style>
