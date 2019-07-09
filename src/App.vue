<template>
  <div class="app">
    <header class="mui-bar mui-bar-nav mui-bar-blue">
			<h1 class="mui-title">首页</h1>
		</header>
    
   <nav class="mui-bar mui-bar-tab">
			<a class="mui-tab-item" to="/home">
				<span class="mui-icon mui-icon-home"></span>
				<span class="mui-tab-label">首页</span>
			</a>
			<a class="mui-tab-item" to="/member">
				<span class="mui-icon mui-icon-contact"></span>
				<span class="mui-tab-label">会员</span>
			</a>
			<a class="mui-tab-item" to="/shopcar">
				<span class="mui-icon mui-icon-extra mui-icon-extra-cart">
					<span class="mui-badge">9</span>
				</span>
				<span class="mui-tab-label">购物车</span>
			</a>
			<a class="mui-tab-item" to="/search">
				<span class="mui-icon mui-icon-gear-filled"></span>
				<span class="mui-tab-label">设置</span>
			</a>
		</nav>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style >
.app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.mui-bar-blue{
    background:#00a1d6;
  }
  .mui-title{
    color: #fff;
  }
</style>
