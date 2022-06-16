<template>
    <div>
        <JumboMain/>
        <ConsultationMain/>
        <BrandMain/>
        <CardMarketing/>
    </div>
</template>

<script>
import JumboMain from '../Section/JumboMain.vue'
import ConsultationMain from '../Section/ConsultationMain.vue'
import BrandMain from '../Section/BrandMain.vue'
import CardMarketing from '../Section/CardMarketing.vue'

export default {
    name:'BaseMain',
    components:{JumboMain, ConsultationMain, BrandMain, CardMarketing,},
}
</script>

<style lang="scss" scoped>

</style>