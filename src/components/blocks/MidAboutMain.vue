<template>
  <div id="container">
    <div class="col_left_mid_about">
        <div class="row_col_left">
            <h2>We Build Relationships</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cumque veritatis adipisci necessitatibus ut libero ipsam, expedita, rerum quia aspernatur facere odio veniam natus nesciunt earum odit nisi illum repudiandae corrupti!</p>
        </div>
        <div class="row_col_left">
            <h2>We Build Relationships</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cumque veritatis adipisci necessitatibus ut libero ipsam, expedita, rerum quia aspernatur facere odio veniam natus nesciunt earum odit nisi illum repudiandae corrupti!</p>
        </div>
    </div>
    <div class="col_right_mid_about">
        <div class="row_col_right">
            <h3>Accountability</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing</p>
        </div>
        <div class="row_col_right">
            <h3>Transparency</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing</p>
        </div>
        <div class="row_col_right">
            <h3>Investment</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing</p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name:'MidAboutMain'
}
</script>

<style lang="scss" scoped>
#container{
    display: flex;
    flex-direction: row;
    gap: 250px;
    padding-bottom: 80px;
    .col_left_mid_about, .col_right_mid_about{
        flex-direction: column;
        width: 45%;
    }
    .col_left_mid_about{
        .row_col_left{
            padding-bottom: 2s0px;
            h2{
                font-size: 1.7rem;
            }
        }
    }
    .col_right_mid_about{
        .row_col_right{
            padding-bottom: 20px;
            h3{
                font-size: 1.4rem;
            }
        }
    }
}
</style>