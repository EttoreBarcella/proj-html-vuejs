<template>
    <div>
        <JumboMain/>
        <ConsultationMain/>
    </div>
</template>

<script>
import JumboMain from '../Section/JumboMain.vue'
import ConsultationMain from '../Section/ConsultationMain.vue'

export default {
    name:'BaseMain',
    components:{JumboMain, ConsultationMain},
}
</script>

<style lang="scss" scoped>

</style>