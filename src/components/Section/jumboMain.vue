<template>
  <section class="bg">
    <div id="container">
        <div class="col_left">
            <h1>unlock your online growth potential </h1>
            <p>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</p>
            <button class="button_jumbo"> Our Services</button>
        </div>
        <div class="col_right">
            <BaseCard/>
        </div>
    </div>
  </section>
</template>

<script>
import BaseCard from '../blocks/BaseCard.vue'

export default {
    components:{BaseCard},
    name:'JumboMain'
}
</script>

<style lang="scss" scoped>
.bg{
    background-image: url('../../assets/Img/marketing-intro.jpg');
    height: 650px;
    background-size: cover;
    background-repeat: no-repeat;
}
#container{
    display: flex;
    width: 1500px;
    margin: auto;
    .col_left{
        width: 40%;
        color: white;
        h1{
            font-size: 4rem;
            text-transform: capitalize;
            margin-bottom: 0;
        }
        p{
            font-size: 1.8rem;
        }
        .button_jumbo{
            background-color: white;
            border: none;
            padding: 15px  40px;
            border-radius: 10px;
            cursor:pointer;
        }
    }
}
</style>