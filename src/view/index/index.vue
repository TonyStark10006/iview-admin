<template>
    <div>
    <Header></Header>
    <!-- start header -->
    <!-- start main -->
    <div class="wrap">
        <div class="wrapper">
            <div class="main">
                <div class="content">
                    <h2 class="style list"><a href="#">Our favourite Task Management App! </a></h2>
                    <h3 class="style">posted on march 28, 2013</h3>
                    <div class="list_img">
                        <img :src="pic1" alt="" align=""/>
                    </div>
                    <p class="para"> All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text.</p>
                    <a href="blog.html" class="btn">Read More</a>
                </div>
                <div class="content">
                    <h2 class="style list"><a href="#">Year in review: Our favourites Apps from 2012</a></h2>
                    <h3 class="style">posted on march 3, 2013</h3>
                    <div class="list_img">
                        <img :src="pic2" alt="" align=""/>
                    </div>
                    <p class="para"> All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text.</p>
                    <a href="blog.html" class="btn">Read More</a>
                </div>
                <div class="content">
                    <h2 class="style list"><a href="#">marketing tips & tricks from the top brands</a></h2>
                    <h3 class="style">posted on December 2, 2013</h3>
                    <div class="list_img">
                        <img :src="pic3" alt="" align=""/>
                    </div>
                    <p class="para"> All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text.</p>
                    <a href="blog.html" class="btn">Read More</a>
                    <!--<div class="pagination">-->
                        <!--<ul>-->
                            <!--<li class="left_arrow" ><a href="#"></a></li>-->
                            <!--<li><a href="#">1</a></li>-->
                            <!--<li><a href="#">2</a></li>-->
                            <!--<li><a href="#">3</a></li>-->
                            <!--<li><a href="#">4</a></li>-->
                            <!--<li><a href="#">5</a></li>-->
                            <!--<li><a href="#">6</a></li>-->
                            <!--<li class="right_arrow"><a href="#"></a></li>-->
                            <!--<div class="clear"></div>-->
                        <!--</ul>-->
                    <!--</div>-->
                </div>
            </div>
        </div>
    </div>
    <!-- start footer -->
        <Footer></Footer>
        <!-- <router-view name="a"></router-view> -->
    </div>

</template>

<script>
import Header from './components/header-bar.vue'
import Footer from './components/footer-bar.vue'
import pic1 from '@/assets/images/index/pic1.jpg'
import pic2 from '@/assets/images/index/pic2.jpg'
import pic3 from '@/assets/images/index/pic3.jpg'
// import $ from 'jquery'

export default {
  name: 'index',
  components: {
    Header: Header,
    Footer: Footer
  },
  created () {
    // console.log($)
  },
  data () {
    return {
      pic1,
      pic2,
      pic3
    }
  }
}
</script>

<style scoped>
/*@import "../../../static/css/reset.css";*/
@import "../../assets/index-style.css";
</style>
