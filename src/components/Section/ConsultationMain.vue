<template>
  <section>
    <div class="container">
        <div class="col_img">
            <img src="" alt="">
        </div>
        <div class="col_text">
            <h2>Increase brand awarness</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae ex sint laborum. Doloremque ullam fugit magni molestias, laudantium aliquam fuga</p>
            <ButtonConsultation/>
        </div>

        <div class="col_text">
            <h2>In-House sales training</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae ex sint laborum. Doloremque ullam fugit magni molestias, laudantium aliquam fuga</p>
            <ButtonConsultation/>
        </div>
        <div class="col_img">
            <img src="" alt="">
        </div>

        <div class="col_img">
            <img src="" alt="">
        </div>
         <div class="col_text">
            <h2>Harness ur social proof</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae ex sint laborum. Doloremque ullam fugit magni molestias, laudantium aliquam fuga</p>
            <ButtonConsultation/>
        </div>
        
        
    </div>
  </section>
</template>

<script>
import ButtonConsultation from '../blocks/ButtonConsultation.vue'
export default {
    components:{ButtonConsultation},
    name:'ConsultationMain',
}
</script>

<style lang="scss" scoped>
.container{
    width: 1500px;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
    .col_img{
        width: 70%;
    }
    .col_text{
        width: 30%;
        h2{
            margin-top: 0;
            font-size: 3rem;
        }
    }  
}
</style>