<template>
  <div>
    <header>
      <h1>お前に聞かせたい曲がある</h1>
    </header>
    <div class="nuxt-container">
      <nuxt/>
    </div>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Noto+Sans+JP|Oswald');
  html {
    font-family: 'Oswald', 'Noto Sans JP', "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    font-size: 16px;
    word-spacing: 1px;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
  }

  body {
    margin: 0;
    border: 20px solid black;
  }

  header {
    font-size: 64px;
  }

  header h1 {
    margin: 0;
    padding: 0.25em 0.5em;
  }

  .nuxt-container {
    min-height: 250px;
  }


  @media(max-width: 710px) {
    header {
      font-size: 34px;
    }

    header h1 {
      padding: 0.25em 0.25em;
    }
  }
</style>
