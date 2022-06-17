<template>
    <div>
        <JumboMain/>
        <ConsultationMain/>
        <BrandMain/>
        <CardMarketing/>
        <TeamMain/>
        <AboutMain/>
        <ReviewMain/>
        <TipsMain/>
        <EndMain/>
    </div>
</template>

<script>
import JumboMain from '../Section/JumboMain.vue'
import ConsultationMain from '../Section/ConsultationMain.vue'
import BrandMain from '../Section/BrandMain.vue'
import CardMarketing from '../Section/CardMarketing.vue'
import TeamMain from '../Section/TeamMain.vue'
import AboutMain from '../Section/AboutMain.vue'
import ReviewMain from '../Section/ReviewMain.vue'
import TipsMain from '../Section/TipsMain.vue'
import EndMain from '../Section/EndMain.vue'

export default {
    name:'BaseMain',
    components:{JumboMain, ConsultationMain, BrandMain, CardMarketing, TeamMain,AboutMain,ReviewMain,TipsMain,EndMain},
}
</script>

<style lang="scss" scoped>

</style>