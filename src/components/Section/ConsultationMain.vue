<template>
  <section>
    <div id="container">
        <div class="col_img">
            <img src="../../assets/Img/92124892-54cc2e00-edcc-11ea-8994-f15925e53b1e.jpg" alt="">
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
            <img class="right_img" src="../../assets/Img/92124892-54cc2e00-edcc-11ea-8994-f15925e53b1e.jpg" alt="">
        </div>

        <div class="col_img">
            <img src="../../assets/Img/92124892-54cc2e00-edcc-11ea-8994-f15925e53b1e.jpg" alt="">
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
#container{
    width: 1500px;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
    .col_img, .col_text{
        height: 550px;
    }
    .col_img{
        width: 50%;
        gap: 20px;
        img{
            height: 50%;
            border-radius: 10px;
        }
        .right_img{
            margin-left: 150px;
        }

    }
    .col_text{
        width: 40%;
        h2{
            font-size: 3rem;
        }
    }  
}
</style>