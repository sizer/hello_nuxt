<template>
  <section class="container">
    <p>
      メガメタルです。
      オススメのヘビメタを投稿します。
      毎日更新できるよう頑張ります！
    </p>
    <div v-html="c20181112" />
  </section>
</template>

<script>
  import c20181112 from '../contents/20181112.md'

  export default {
    components: {},
    computed: {
      c20181112() {
        return c20181112
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
