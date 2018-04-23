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
          <!-- 文章列表 -->
          <div class="list-container">
            <ul class="note-list">
              <li class="have-img">
                <nuxt-link to="/p/123" class="wrap-img">
                  <img src="~/assets/img/note.png" alt="">
                </nuxt-link>
                <div class="content">
                  <div class="author">
                    <nuxt-link to="/p/123" class="avatar">
                      <img src="~/assets/img/1.jpg" alt="">
                    </nuxt-link>
                    <div class="info">
                        <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                        <span class="time">
                          04.12 10:18
                        </span>
                    </div>
                  </div>
                  <nuxt-link to="/u/123" class="title">实现一个靠谱的Web认证</nuxt-link>
                  <div class="abstruct">Web认证是任何一个认真一点的网站都必须实现的基本功能。这个功能解决了让服务器“认识你就是你“的问题。这个功能看起来貌似很简单，但是实际上处处是坑。因为认证是依靠一套技术整体...</div>
                  <div class="meta">
                    <nuxt-link to="/u/123" class="collection-tag">程序员</nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-eye"></i>
                      1500
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-comment"></i>
                      100
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-heart"></i>
                      20
                    </nuxt-link>
                  </div>
                </div>
              </li>
              <li>
                <div class="content">
                  <div class="author">
                    <nuxt-link to="/p/123" class="avatar">
                      <img src="~/assets/img/1.jpg" alt="">
                    </nuxt-link>
                    <div class="info">
                        <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                        <span class="time">
                          04.12 10:18
                        </span>
                    </div> 
                  </div>
                  <nuxt-link to="/u/123" class="title">实现一个靠谱的Web认证</nuxt-link>
                  <div class="abstruct">Web认证是任何一个认真一点的网站都必须实现的基本功能。这个功能解决了让服务器“认识你就是你“的问题。这个功能看起来貌似很简单，但是实际上处处是坑。因为认证是依靠一套技术整体...</div>
                  <div class="meta">
                    <nuxt-link to="/p/123">
                      <i class="fa fa-eye"></i>
                      1500
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-comment"></i>
                      100
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-heart"></i>
                      20
                    </nuxt-link>
                  </div>
                </div>
              </li>
              <li class="have-img">
                <nuxt-link to="/p/123" class="wrap-img">
                  <img src="~/assets/img/note.png" alt="">
                </nuxt-link>
                <div class="content">
                  <div class="author">
                    <nuxt-link to="/p/123" class="avatar">
                      <img src="~/assets/img/1.jpg" alt="">
                    </nuxt-link>
                    <div class="info">
                        <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                        <span class="time">
                          04.12 10:18
                        </span>
                    </div>
                  </div>
                  <nuxt-link to="/u/123" class="title">实现一个靠谱的Web认证</nuxt-link>
                  <div class="abstruct">Web认证是任何一个认真一点的网站都必须实现的基本功能。这个功能解决了让服务器“认识你就是你“的问题。这个功能看起来貌似很简单，但是实际上处处是坑。因为认证是依靠一套技术整体...</div>
                  <div class="meta">
                    <nuxt-link to="/u/123" class="collection-tag">程序员</nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-eye"></i>
                      1500
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-comment"></i>
                      100
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-heart"></i>
                      20
                    </nuxt-link>
                  </div>
                </div>
              </li>
              <li>
                <div class="content">
                  <div class="author">
                    <nuxt-link to="/p/123" class="avatar">
                      <img src="~/assets/img/1.jpg" alt="">
                    </nuxt-link>
                    <div class="info">
                        <nuxt-link to="/u/123" class="nickname">测试用户</nuxt-link>
                        <span class="time">
                          04.12 10:18
                        </span>
                    </div> 
                  </div>
                  <nuxt-link to="/u/123" class="title">实现一个靠谱的Web认证</nuxt-link>
                  <div class="abstruct">Web认证是任何一个认真一点的网站都必须实现的基本功能。这个功能解决了让服务器“认识你就是你“的问题。这个功能看起来貌似很简单，但是实际上处处是坑。因为认证是依靠一套技术整体...</div>
                  <div class="meta">
                    <nuxt-link to="/p/123">
                      <i class="fa fa-eye"></i>
                      1500
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-comment"></i>
                      100
                    </nuxt-link>
                    <nuxt-link to="/p/123">
                      <i class="fa fa-heart"></i>
                      20
                    </nuxt-link>
                  </div>
                </div>
              </li>
            </ul>
            <a href="#" class="load-more">阅读更多</a>
          </div>
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
