<template>
 <div>
	  <header class="flexbox">
	     <div class="flex_s">哈喽2342</div>
	     <div><img src="../assets/sous_img.png" class="shous"></div>
	  </header>
	  <div>
		  <ul>
		  	<router-link to="">时下流行</router-link>
		  	<router-link to="">歌单</router-link>
		  	<router-link to="">排行榜</router-link>
		  	<router-link to="">热门歌手</router-link>
		  </ul>
		  <router-view></router-view>
	  </div>
 </div>
</template>
<script src="../assets/js/rem.js"></script>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
<style scoped>
@import "../assets/css/public_style.css"
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
header{
	background:#ce3d3e ;
	height:40px;
	line-height: 40px;
	color:#fff;
	font-size: 14px;
	
}
.shous{
	width:0.3rem;
	height:0.3rem;
	margin: 0 0.2rem;
	vertical-align: middle;
}
</style>
