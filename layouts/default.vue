<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');

html {
  font-family: 'Roboto Mono', monospace;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #000000;
  height: 100vh;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--white {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #ffffff;
  color: #ffffff;
  text-decoration: none;
  padding: 10px 30px;
  transition: 0.3s ease-in-out;
}

.button--white:hover {
  color: #000000;
  background-color: #ffffff;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.white {
  color: #fff;
}
</style>
