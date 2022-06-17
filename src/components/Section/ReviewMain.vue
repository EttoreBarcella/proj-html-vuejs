<template>
  <section>
    <div id="container_review">
        <div class="box_img">
            <img src="../../assets/Img/large-testimonial-600x583.jpg" alt="">
        </div>
        <div class="box_text">
            <h2>"The team at Avada Marketing consultant is faboulus. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progreessive approach"</h2>
            <h3>Kate Schadler</h3>
            <small>Marketing Consultant-Abstract</small>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name:'ReviewMain',
}
</script>

<style lang="scss" scoped>
#container_review{
    max-width: 1400px;
    margin:auto;
    display: flex;
    flex-direction: row;
    margin-top: 100px;
    margin-bottom: 100px;
    .box_img{
        width: 50%;
        img{
            border-radius: 10px;
        }
    }
    .box_text{
        width: 50%;
        h2{
            margin-right: 100px;
            font-size: 1.8rem;
            margin-top: 150px;
            margin-bottom: 10px;
        }
    }
}
</style>