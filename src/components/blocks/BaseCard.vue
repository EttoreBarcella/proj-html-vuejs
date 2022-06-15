<template>
    <section>
        <div class="container_card">
            <div class="img_card">
                <img src="../../assets/Img/marketing-consultant-expert.jpg" alt="">
            </div>
            <h2>Richard Madsen</h2>
            <h4>Marketing Consultant Expert</h4>
            <a href="#">(555)802-1234</a>
            <br>
            <input type="text" placeholder="Your Name*">
            <input type="text" placeholder="Your Email*">
            <input type="text" placeholder="Your Phone Number*">
            <br>
            <ButtonCard/>
            <br>
            <small>By submitting my data i agree to be contacted</small>
        </div>
    </section>
</template>

<script>
import ButtonCard from './ButtonCard.vue'
export default {
    components:{ButtonCard},
    name:'BaseCard',
}
</script>

<style lang="scss" scoped>
    .container_card{
        background-color: white;
        height: 600px;
        width: 450px;
        margin-left: 200px;
        margin-top: 70px;
        box-shadow: 0px 13px 23px -3px rgba(0,0,0,0.62);
        text-align: center;
        border-radius: 10px;
        h2{
            color: black;
        }
        h4{
            color: grey;
            font-weight: lighter;
        }
        small{
            color: grey;
        }
        small:hover{
            text-decoration: underline;
            color: grey;
            cursor: pointer;
        }
        a{
            text-decoration: none;
            color: #f76210;
        }
        a:hover{
            color: #f76210;
            text-decoration: underline;
        }
        img{
            border-radius: 50%;
            margin-top: 50px;
            width: 20%;
        }
        input[type=text] {
            width: 80%;
            padding: 15px 20px;
            margin: 10px 0;
            border-radius: 10px;
            border: 1px solid gray;
        }
    }
</style>    