<template>
  <section id="container">
    <div class="team_title">
        <h1>Trusted by Leading Organisations</h1>
    </div>
    <div class="card_container">
        <div class="team_col_left">
            <div class="team_card_img">
                <img  src="../../assets/Img/case-studies-1.jpg" alt="">
            </div>
            <p>How Spaces attracted five million visitors by improving the content</p>
            <hr>
            <h2>200%</h2>
            <small>Higer revenue from digital</small>
        </div>
        <div class="team_col_middle">
            <div class="team_card_img">
                <img src="../../assets/Img/case-studies-4.jpg" alt="">
            </div>
            <p>Creativity helped Hemisferio to increase their brand reach vertically</p>
            <hr>
            <h2>10x</h2>
            <small>Sales increase with the same ad spend</small>
        </div>
        <div class="team_col_right">
            <div class="team_card_img">
                <img src="../../assets/Img/case-studies-6.jpg" alt="">
            </div>
            <p>How DigitalBox used AI-powered data insight to boost sales</p>
            <hr>
            <h2>3-year</h2>
            <small>Partnership with avada consultant</small>
        </div>
        <div class="team_button">
            <ButtonTeam/>
        </div>
    </div>
  </section>
</template>

<script>
import ButtonTeam from '../blocks/ButtonTeam.vue'
export default {
    name:'TeamMain',
    components:{ButtonTeam}
}
</script>

<style lang="scss" scoped>
#container{
    max-width: 1500px;
    margin: auto;
    .team_title{
        text-align: center;
        h1{
            font-size: 3rem;
        }
    }
    .card_container{
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        gap: 50px;
        .team_col_left, .team_col_middle, .team_col_right{
            width: calc(100% / 3 - 35px);
            p{
                font-size: 1.5rem;font-weight: bold;
            }
            hr{
                border-top: dashed 1px grey;
            }
            h2{
                font-size: 2.5rem;
                margin-bottom: 0;
            } 
            small{
                font-size: 1rem;
            }
        }
    }
    .team_card_img{
        img{
            width:100%;
        }
    }
    .team_button{
        margin: auto;
        text-align: center;
    }
}
</style>