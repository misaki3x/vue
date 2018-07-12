<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!-- <router-link to="/">ホーム</router-link> -->
    <!-- <router-link to="/service">サービス</router-link> -->
    <router-link to="/news">ニュース</router-link>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'ニュースページ'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1, h2 {
      font-weight: normal;
    }

    a {
      color: #42b983;
    }
</style>
