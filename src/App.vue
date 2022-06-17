<template>
  <div>
    <BaseHeader/>
    <BaseMain/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/Header/BaseHeader.vue'
import BaseMain from './components/Main/BaseMain.vue'
import BaseFooter from './components/Footer/BaseFooter.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BaseFooter
  }
}
</script>

<style lang="scss" scoped>
div{
  font-family: 'Roboto', sans-serif;
}
@import './assets/Style/global.scss'

</style>
