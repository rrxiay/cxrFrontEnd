<template>
  <div class="index">
    <globalHeader></globalHeader>
    <a
      href="https://vuejs.org"
      target="_blank"
    >
      Core Docs
    </a>

    <globalFooter></globalFooter>

  </div>
</template>

<script>

  import Footer from '../global/Footer'
  import Header from '../global/Header'
  export default {
    name: 'Index',
    components:{
      GlobalHeader:Header,
      GlobalFooter:Footer,
    },
    data () {
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
</style>
