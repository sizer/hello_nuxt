<template>
  <section class="container">
    <p>
      メガメタルです。
      オススメのヘビメタを投稿します。
      毎日更新できるよう頑張ります！
    </p>
    <div v-html="hello" />
  </section>
</template>

<script>
  import hello from '../contents/hello.md'

  export default {
    components: {},
    computed: {
      hello() {
        return hello
      }
    }
  }
</script>

<style>
  .container {
    width: 80%;
    margin: 0 auto;
  }
</style>
