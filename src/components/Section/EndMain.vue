<template>
  <section>
    <div id="container_end">
        <div class="col_end_left">
            <h1>Let's Make Things Happen</h1>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Id excepturi vel porro perferendis asperiores quos numquam rem doloremque tenetur sint, placeat cumque nihil corporis debitis hic dignissimos sunt, dolores incidunt?</p>
            <hr>
            <p><i>"Lorem ipsum dolor sit amet consectetur adipisicing elit. In ipsam nobis vero cupiditate maxime veritatis. Tenetur aut pariatur optio dolore recusandae reprehenderit culpa saepe doloremque quod tempore laborum, nemo sequi!"</i></p>
            <h4>George Anderson</h4>
            <small>Digital Box Ceo</small>
        </div>
        <div class="col_end_right">
            <BaseCard class="card_end"/>
        </div>
    </div>
  </section>
</template>

<script>
import BaseCard from '../blocks/BaseCard.vue'
export default {
    name:'EndMain',
    components:{BaseCard}
}
</script>

<style lang="scss" scoped>
section{
    background-color: black;
    #container_end{
        padding-top: 100px;
        width: 1500px;
        margin: auto;
        display: flex;
        flex-direction: row;
        gap: 100px;
        .col_end_left{
            width: 50%;
            h1{
                font-size: 3.5rem;
                color: white;
            }
            p{
                padding-right: 80px;
                font-size: 1.6rem;
                color: white;
                margin-bottom: 50px;
                margin-top: 50px;
            }
            hr{
                width: 20%;
                margin-left: 0;
                border-bottom: 1px solid grey;
            }
            h4{
                color: white;
                margin-bottom: 5px;
            }
            small{
                color: grey;
            }
        }
        .col_end_right{
            height: 700px;
        }
    }
}
</style>

