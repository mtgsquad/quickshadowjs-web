<template>
    <div class="container">
      <div class="topContainer">
      <div class="top">
        <a class="white" href="/">Go back home</a>
      </div>
      </div>
      <br>
      <div class="middleof-top">
        <h1>Documentation</h1>
      </div>
      <div class="textbox">
        <h2 class="setup-heading white">
          Setup
        </h2>
        <br>
        <p class="setup-para white">
          Just add the <code>quickshadow</code> class to your element to give it shadows!
        </p>
        <br>
        <h2 class="white config-heading">
          Configuration
        </h2>
        <br>
        <p class="white config-para">
          The Configuration Is Extremely Easy, these settings will apply to all of your shadows.
          <br>
          You have to link the JavaScript configuration file in your head with: <code>&lt;script src="path/to/javascript/file.js" defer&gt;&lt;/script&gt;</code>
          <br>
          This is what your configuration file should look like:
          <br>
          <code lang="text/javascript">
            import { quickshadow } from 'quickshadow';
            <br>
            quickshadow({
              <br>
              shadow_type: 'soft',
              <br>
              padding: true
              <br>
            });
          </code>
        </p>
      </div>
      <br>
    </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 35vh;
  position: relative;
}

h1 {
  font-family: 'Roboto Mono', monospace;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #ffffff;
  letter-spacing: 1px;
}

.margin-45px {
  margin: 45px;
}

.middleof-top {
  position: absolute;
  top: 105px;
  left: 290px;
  transform: translate(-50, -50);
}

.textbox {
  margin: 0 auto;
  min-height: 620px;
  display: flex;
  position: relative;
}

.setup-heading {
  position: absolute;
  top: 42%;
  left: 265px;
  font-size: 34px;
}

.setup-para {
  position: absolute;
  top: 51%;
  left: 275px;
  font-size: 24px;
}

.config-heading {
  position: absolute;
  top: 60%;
  left: 265px;
  font-size: 34px;
}

.config-para {
  position: absolute;
  top: 69%;
  left: 275px;
  font-size: 24px;
}

code {
  color: rgb(116, 108, 108);
}

.topContainer {
  position: relative;
}

.top {
  position: absolute;
  top: 15px;
  left: 50%;
  transform: translateX(-50, -50);
}
</style>