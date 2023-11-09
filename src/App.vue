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
</template>

<script>

import Header from './components/Header.vue';
import ContentHere from './components/ContentHere.vue';
import Merch from './components/Merch.vue';
export default {
  name:'App',
  components: {
    Header,
    ContentHere,
    Merch,
    
  },
  data () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>