<template>
  <div class="wrapper">
    <!-- 头部信息 -->

    <!--头部导航-->
    <header>
      <div class="sui-navbar">
        <div class="navbar-inner">
          <a href="/" class="sui-brand">
            <img src="~/assets/img/asset-logo-black.png" alt="社交" />
          </a>
          <ul class="sui-nav">
            <router-link tag="li" to="/" active-class="active" exact>
              <a>首页</a>
            </router-link>
            <router-link tag="li" to="/interactive" active-class="active">
              <a>互动</a>
            </router-link>
            <router-link tag="li" to="/Resources" active-class="active">
              <a>资源</a>
            </router-link>
            <!-- <router-link tag="li" to="/friend" active-class="active">
              <a>交友</a>
            </router-link>
            <router-link tag="li" to="/spit" active-class="active">
              <a>吐槽</a>
            </router-link>
            <router-link tag="li" to="/recruit" active-class="active">
              <a>招聘</a>
            </router-link> -->
          </ul>
          <form class="sui-form sui-form pull-left">
            <input type="text" placeholder="输入关键词..." />
            <span class="btn-search fa fa-search"></span>
          </form>
          <div class="sui-nav pull-right info">
            <li>
              <a href="~/assets/other-notice.html" target="_blank" class="notice">通知</a>
            </li>
            <li class="hover">
              <span class="fa fa-plus"></span>
              <ul class="hoverinfo">
                <li>
                  <i class="fa fa-share-alt" aria-hidden="true"></i>
                  <a href="~/assets/headline-submit.html">去分享</a>
                </li>
                <li>
                  <i class="fa fa-question-circle" aria-hidden="true"></i>
                  <a href="~/assets/qa-submit.html" target="_blank">提问题</a>
                </li>
                <li>
                  <i class="fa fa-comments" aria-hidden="true"></i>
                  <a href="~/assets/spit-submit.html" target="_blank">去吐槽</a>
                </li>
                <li>
                  <i class="fa fa-heartbeat" aria-hidden="true"></i>
                  <a href="~/assets/makeFriends-submit.html" target="_blank">发约会</a>
                </li>
              </ul>
            </li>
            <li>
              <a href="~/assets/person-homepage.html" target="_blank" class="homego">
                <img src="~/assets/img/widget-photo.png" alt="用户头像" />
              </a>
            </li>
          </div>
        </div>
      </div>
    </header>
    <!-- 头部信息 -->

    <nuxt />
    <!-- 尾部信息 -->
    <div class="footer">
      <div class="wrapper">
        <div class="footer-bottom">
          <div class="link">
            <dl>
              <dt>网站相关</dt>
              <dd>关于我们</dd>
              <dd>服务条款</dd>
              <dd>帮助中心</dd>
              <dd>编辑器语法</dd>
            </dl>
            <dl>
              <dt>常用链接</dt>
              <dd>百度网盘</dd>
              <dd>阿里云</dd>
            </dl>
            <dl>
              <dt>联系我们</dt>
              <dd>联系我们</dd>
              <dd>加入我们</dd>
              <dd>建议反馈</dd>
            </dl>
            <dl>
              <dt>关注我们</dt>
              <dd>微博</dd>
              <dd>twitter</dd>
            </dl>
            <div class="xuke">
              <h3>内容许可</h3>
              <p>除特别说明外，用户内容均采用知识共享署名-非商业性使用-禁止演绎4.0 国际许可协议 (CC BY-NC-ND 4.0) 进行许可</p>
              <p>本站由 Yinn 提供更新服务</p>
            </div>
          </div>
          <p class="Copyright">Copyright &copy; 2019 Yinn 当前版本 0.0.1</p>
        </div>
      </div>
    </div>
    <!-- 尾部信息 -->
  </div>
</template>
<script>
import "~/assets/plugins/normalize-css/normalize.css";
import "~/assets/plugins/yui/cssgrids-min.css";
import "~/assets/plugins/sui/sui.min.css";
import "~/assets/plugins/sui/sui-append.min.css";
import "~/assets/plugins/font-awesome/css/font-awesome.min.css";
import "~/assets/css/widget-base.css";
import "~/assets/css/widget-head-foot.css";
export default {};
</script>
<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>

