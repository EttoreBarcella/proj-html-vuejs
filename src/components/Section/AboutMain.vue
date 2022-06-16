<template>
  <section>
    <div id="container">
        <TopAboutMain/>
        <MidAboutMain/>
        <BotAboutMain/>
    </div>
  </section>
</template>

<script>
import TopAboutMain from '../blocks/TopAboutMain.vue'
import MidAboutMain from '../blocks/MidAboutMain.vue'
import BotAboutMain from '../blocks/BotAboutMain.vue'
export default {
    name:'AboutMain',
    components: {TopAboutMain,MidAboutMain,BotAboutMain,}
}
</script>

<style lang="scss" scoped>
section{
    background-color: #f6f6f7;
    #container{
        max-width: 1400px;
        margin:auto;
    }
}
</style>