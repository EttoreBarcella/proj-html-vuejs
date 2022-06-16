<template>
  <div id="container">
    <div class="top_about_left">
        <h2>We Boost Our Clients' Bottom Line by Optimizing Their Growth Potential.</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vel officia ea quas necessitatibus, rerum commodi minus quidem nemo deleniti molestiae itaque perspiciatis dicta, aut porro, iure neque. Aliquid, excepturi magni?</p>
        <button class="top_about_button">Why work with us</button>
    </div>
    <div class="top_about_right">
        <div class="box_img">
            <img src="../../assets/Img/we-boost-our-clients.jpg" alt="">
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name:'TopAboutMain'
}
</script>

<style lang="scss" scoped>
#container{
    display: flex;
    padding-top: 100px;
    padding-bottom: 50px;
    flex-wrap: wrap;
    justify-content: space-between;
    .top_about_left{
        width: 45%;
        h2{
            font-size: 3.2rem;
        }
        .top_about_button{
            background-color: #f76210; 
            color: white;  
            border: none;
            border-radius: 10px;
            padding: 10px 40px;
            cursor: pointer;
        }
    }
    .top_about_right{
        width: 55%;
        .box_img{
            height: 450px;
            padding-left: 250px;
            img{
                height: 100%;
                border-radius: 20px;
            }
        }
    }
}
</style>