<template>
  <div>
    <header>
      <h1>MEGAHAGE!!</h1>
      <nav>
        <nuxt-link to="/contents">contents</nuxt-link>
        <nuxt-link to="/profile">profile</nuxt-link>
      </nav>
    </header>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
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
}
header {
  background-color: black;
  color: white;
}

header h1 {
  margin: 0;
  padding: 0.5em;
}
</style>
