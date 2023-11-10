<template>
  <div>
   <Header></Header>
  </div>
  <div>
    <ContentHere></ContentHere>
  </div>
  <div>
    <Merch></Merch>
  </div>
  <div>
    <MainDc></MainDc>
  </div>
  <div>
    <Footer></Footer>
  </div>
</template>

<script>

import Header from './components/Header.vue';
import ContentHere from './components/ContentHere.vue';
import Merch from './components/Merch.vue';
import MainDc from './components/MainDc.vue';
import Footer from './components/Footer.vue';

export default {
  name:'App',
  components: {
    Header,
    ContentHere,
    Merch,
    MainDc,
    Footer,
  },
  data () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>