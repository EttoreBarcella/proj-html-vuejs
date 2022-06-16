<template>
  <section id="container">
    <div class="card_image">
        <img src="../../assets/Img/marketing-expert-cta.png" alt="">
    </div>
    <div class="card_info">
        <h4>Sandy Reiff</h4>
        <small>marketing consultant expert</small>
    </div>
    <div class="card_job">
        <h2>Drive Leads and Sales with Avada</h2>
    </div>
    <div class="card_button">
        <ButtonMarketing/>
    </div>
  </section>
</template>

<script>
import ButtonMarketing from '../blocks/ButtonMarketing.vue'
export default {
    name:'CardMarketing',
    components:{ButtonMarketing},
}
</script>

<style lang="scss" scoped>
#container{
    width: 1500px;
    margin: auto;
    display: flex;
    box-shadow: 0px 15px 23px -3px rgba(0,0,0,0.7);
    border-radius: 10px;
    height: 80px;
    align-items: center;
    .card_image{
        margin-left: 90px;
        img{
            height: 60px;
            border-radius: 50%;
            
        }
    }
    .card_info{
        margin-left: 20px;
        h4{
            margin: 0;
        }
        small{
            color: grey;
        }
    }
    .card_job{
        margin-left: 250px;
    }
    .card_button{
        margin-left: 300px;
    }
}
</style>