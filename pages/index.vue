<template>
  <div style="height:100%">
    <my-header></my-header>
    <div class="container index">
      <div class="row">
        <div class="col-xs-16 main">
          <!-- 热门专题 -->
          <div class="recommend-collection">
            <nuxt-link to="/collection/123" class="collection">
              <img src="~/assets/img/c_1.jpg" alt="">
              <span name="name">故事</span>
            </nuxt-link>
            <nuxt-link to="/collection/123" class="collection">
              <img src="~/assets/img/c_1.jpg" alt="">
              <span name="name">摄影</span>
            </nuxt-link>
            <nuxt-link to="/collection/123" class="collection">
              <img src="~/assets/img/c_2.jpg" alt="">
              <span name="name">人文社科</span>
            </nuxt-link>
            <nuxt-link to="/collection/123" class="collection">
              <img src="~/assets/img/c_2.jpg" alt="">
              <span name="name">历史</span>
            </nuxt-link>
            <nuxt-link to="/collection/123" class="collection">
              <img src="~/assets/img/c_3.jpg" alt="">
              <span name="name">读书</span>
            </nuxt-link>
            <nuxt-link to="/collextion/123" class="more-collection">
              更多热门专题
              <i class="fa fa-angle-right"></i>
            </nuxt-link>
          </div>
          <div class="split-line"></div>
        </div>
        <div class="col-xs-offset-1 col-xs-7 aside">
          侧边栏
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import myHeader from '../components/myHeader'

export default {
  head:{
    title:'简书-创作你的创作',
    meta:[
      { charset: "utf-8" },
      { name: "keywords", content: "简书首页" },
      { name: "description", content: "简书首页" },
      { name: "author", content: "王雪金" }
    ]
  },
  components:{
    myHeader
  },
  data () {
    return{
      name:'首页'
    }
  }
}
</script>

<style scoped>

</style>
