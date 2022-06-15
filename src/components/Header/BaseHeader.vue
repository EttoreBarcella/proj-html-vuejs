<template>
    <header class="container">
        <div class="logo_box">
            <img class="logo_header" src="../../assets/Img/avada-marketing-logo.png" alt="asdas">
        </div>
        <nav>
            <ul class="header_nav">
                <li v-for="(link,index) in links" :key="index">
                    <a :href="link.url">{{link.text}}<FontAwesomeIcon :icon="link.icon"/></a>
                </li>
            </ul> 
        </nav>
    </header>
</template>

<script>

export default{
    name: 'BaseHeader',
    data(){
        return {
            links: [
                {
                    text: 'Home',
                    url: '#',
                    icon: 'fa-solid fa-angle-down',
                    
                },
                {
                    text: 'Services',
                    url: '#',
                    icon: "fa-solid fa-angle-down",
                },
                {
                    text: 'Why Us',
                    url: '#',
                    icon: '',
                },
                {
                    text: 'Case Studies',
                    url: '#',
                    icon: '',
                },
                {
                    text: 'About',
                    url: '#',
                    icon: '',
                },
                {
                    text: 'Blog',
                    url: '#',
                    icon: '',
                },
                {
                    text: '(555)802-1234',
                    url: '#',
                    icon: '',
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
.container{
  display: flex;
  .logo_box{
    display: flex;
    align-items: center;
  }
  .header_nav{
    display: flex;
    list-style: none;
    align-items: center;
    gap: 30px;
    a{
      color: #424242;
      font-size: 1.2rem;
      text-decoration: none;
    }
    a:hover{
      color: #f76210;
      text-decoration: underline;
    }
  }
}
</style>