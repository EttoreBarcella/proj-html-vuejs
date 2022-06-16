<template>
  <section id="container">
    <div class="brand_title">
        <h1>Some Brands We Work With</h1>
        <h3>Quisque aliquet, libero consequat elementum convallis</h3>
    </div>
    <ul class="brand_list">
        <li>
          <img src="../../assets/Img/abstract.png" alt="">  
        </li>
        <li>
          <img src="../../assets/Img/cglobal.png" alt="">  
        </li>
        <li>
          <img src="../../assets/Img/next.png" alt="">  
        </li>
        <li>
          <img src="../../assets/Img/hemisferio.png" alt="">  
        </li>
        <li>
          <img src="../../assets/Img/spaces.png" alt="">  
        </li>
        <li>
          <img src="../../assets/Img/digitalbox.png" alt="">  
        </li>
    </ul>
  </section>
</template>

<script>
export default {
    name:'BrandMain',

}
</script>

<style lang="scss" scoped>
#container{
    width: 1500px;
    margin: auto;
    .brand_title{
        text-align: center;
        h1{
            font-size: 3.5rem;
        }
    }
    .brand_list{
        list-style: none;
        display: flex;
        margin-bottom: 100px;
        img{
            padding: 20px;
            cursor: pointer;
        }
    }
}
</style>