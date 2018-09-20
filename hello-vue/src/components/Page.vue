<template>
  <div class="page container-fluid">
   <Header></Header>
   <Main></Main>
   <Footer></Footer>
  </div>
</template>

<script>
import Header from './layoutPageComponent/Header.vue';
import Main from './layoutPageComponent/Main.vue';
import Footer from './layoutPageComponent/Footer.vue';

export default {
  name: 'Page',
  data () {
    return {
    }
  },
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

h1, h2 {
  font-weight: normal;
  color: red;
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
