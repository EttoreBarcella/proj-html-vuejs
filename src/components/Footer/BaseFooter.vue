<template>
  <section>
    <div id="container_footer">
      <div class="col_text_footer">
        <h2>Grow Your Online Business Strategically, and Improve Customer Retention.</h2>
      </div>
      <div class="col_links">
        <ul>
          <li><b>Services</b></li>
          <li><a href="#">Marketing Plan</a></li>
          <li><a href="#">Sales Development</a></li>
          <li><a href="#">Digital Marketing</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Why Us</a></li>
          <li><a href="#">Case Studies</a></li>
        </ul>
      </div>
      <div class="col_links">
        <ul>
          <li><b>Resources</b></li>
          <li><a href="#">Learning Center</a></li>
          <li><a href="#">Video Tutorials</a></li>
          <li><a href="#">Customers</a></li>
          <li><a href="#">Blog</a></li>
        </ul>
      </div>
      <div class="col_links">
        <ul>
          <li><b>Company</b></li>
          <li><a href="#">Who We Are</a></li>
          <li><a href="#">Contact US</a></li>
          <li><a href="#">Careers</a></li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name:'BaseFooter'
}
</script>

<style lang="scss" scoped>
#container_footer{
  width: 1500px;
  margin: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  padding-top: 100px;
  gap: 50px;
  .col_text_footer{
    width: 30%;
  }
  .col_links{
    width: calc(70% / 3 - 50px);
    ul{
      list-style: none;
      li{
        padding: 5px;
        display: flex;
      }
      a{
        text-decoration: none;
        color: black;
      }
      a:hover{
        text-decoration: underline;
        color: black;
      }
    }
  }
}
</style>