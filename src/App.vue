<template>
  <div id="app">
    <FooterGuider v-show="$route.meta.showFooter"/>
    <router-view/>
  </div>
</template>

<script>
import FooterGuider from './components/FooterGuide/FooterGuide.vue'
export default {
  components: {
    FooterGuider
  }
}
</script>

<style lang="stylus" ref="stylesheet/stylus">
.app
  width 100%
  height 100%
  background #f5f5f5
</style>
