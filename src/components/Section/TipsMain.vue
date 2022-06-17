<template>
    <section>
        <div id="container_tips">
            <div class="text_col">
                <h2>Marketing Resources: <br>
                    Insider Advice on How to Increase Online Sales</h2>
            </div>
            <div class="button_col">
                <ButtonTips/>
            </div>
        </div>
        <div class="box_tips">
            <div class="card_tips">
                <div class="box_img">
                    <img src="../../assets/Img/blog-posts-6-400x267.jpg" alt="">
                </div>
                <div class="text_img">
                    <h3>Marketing Tips and Tricks For Your Website</h3>
                </div>
            </div>
            <div class="card_tips">
                <div class="box_img">
                    <img src="../../assets/Img/blog-posts-5-400x267.jpg" alt="">
                </div>
                <div class="text_img">
                    <h3>Marketing Tips and Tricks For Your Website</h3>
                </div>
            </div>
            <div class="card_tips">
                <div class="box_img">
                    <img src="../../assets/Img/blog-posts-4-400x267.jpg" alt="">
                </div>
                <div class="text_img">
                    <h3>Marketing Tips and Tricks For Your Website</h3>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import ButtonTips from '../blocks/ButtonTips.vue'
export default {
    name:'TipsMain',
    components:{ButtonTips,}
}
</script>

<style lang="scss" scoped>
section{
    background-color: #f6f6f7;
    #container_tips{
        width: 1500px;
        margin: auto;
        padding-top: 100px;
        display: flex;
        padding-bottom: 100px;
        .text_col{
            width: 40%;
            h2{
                font-size: 2.5rem;
                margin-bottom: 0;
            }
        }
        .button_col{
            width: 60%;
            display: flex;
            align-items: flex-end;
            justify-content: flex-end;
            margin-right: 100px;
        }
    }
    .box_tips{
        width: 1500px;
        margin: auto;
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        padding-bottom: 100px;
        .card_tips{
            width: calc(100% / 3);  
            display: flex;
            flex-direction: column;
            .box_img{
                width: 100%;
            }
            h3{
                font-size: 1.5rem;
                margin-right: 50px;
            }
        }
    }
}
</style>