<template>
    <div>
        <JumboMain/>
        <ConsultationMain/>
        <BrandMain/>
        <CardMarketing/>
        <TeamMain/>
    </div>
</template>

<script>
import JumboMain from '../Section/JumboMain.vue'
import ConsultationMain from '../Section/ConsultationMain.vue'
import BrandMain from '../Section/BrandMain.vue'
import CardMarketing from '../Section/CardMarketing.vue'
import TeamMain from '../Section/TeamMain.vue'

export default {
    name:'BaseMain',
    components:{JumboMain, ConsultationMain, BrandMain, CardMarketing, TeamMain,},
}
</script>

<style lang="scss" scoped>

</style>