<template>
  <div id="app">
    <BaseHeader/>
    <BaseMainTop/>
    <BaseMainBottom/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue'
import BaseMainTop from './components/BaseMainTop.vue'
import BaseMainBottom from './components/BaseMainBottom.vue'
import BaseFooter from './components/BaseFooter.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMainTop,
    BaseMainBottom,
    BaseFooter,
  }
}
</script>

