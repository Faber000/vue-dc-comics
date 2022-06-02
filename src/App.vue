<template>
  <div id="app">
    <BaseHeader/>
    <BaseMainTop/>
    <BaseMainBottom/>
    <BaseFooterTop/>
    <BaseFooterBottom/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue'
import BaseMainTop from './components/BaseMainTop.vue'
import BaseMainBottom from './components/BaseMainBottom.vue'
import BaseFooterTop from './components/BaseFooterTop.vue'
import BaseFooterBottom from './components/BaseFooterBottom.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMainTop,
    BaseMainBottom,
    BaseFooterTop,
    BaseFooterBottom,
  }
}
</script>

<style lang="scss">
@import './assets/style/style.scss';
</style>

