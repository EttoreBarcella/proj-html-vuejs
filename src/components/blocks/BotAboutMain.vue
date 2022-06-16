<template>
  <div id="container">
    <div class="title_bot_about_main">
      <h1>Awards</h1>
    </div>
    <div class="container_awards">
      <div class="award">
        <img class="first_award" src="../../assets/Img/award-a-200x191.png" alt="">
        <small>Winner Seo Master MAGT</small>
        <br>
        <small>Smart Start Award 2017</small>
      </div>
      <div class="award">
        <img src="../../assets/Img/award-b-200x191.png" alt="">
        <small>Winner Seo Master MAGT</small>
        <br>
        <small>Smart Start Award 2017</small>
      </div>
      <div class="award">
        <img src="../../assets/Img/award-c-200x191.png" alt="">
        <small>Winner Seo Master MAGT</small>
        <br>
        <small>Smart Start Award 2017</small>
      </div>
      <div class="award">
        <img class="first_award" src="../../assets/Img/award-d-200x191.png" alt="">
        <small>Winner Seo Master MAGT</small>
        <br>
        <small>Smart Start Award 2017</small>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name:'BotAboutMain',
}
</script>

<style lang="scss" scoped>
#container{
  padding-bottom: 150px;
  .title_bot_about_main{
    text-align: center;
  }
  .container_awards{
    display: flex;
    flex-wrap: wrap;    
    justify-content: space-between;                 
    .award{
      max-width: calc(100% / 4);
      text-align: center;
      img{
        display: block;
      }
      .first_award{
        filter: invert(100%);
      }
    }
  }
}
</style>