<script>
	export default{
		onLaunch: function(){
			console.warn('当前组件仅支持 uni_modules 目录结构 ，请升级 HBuilderX 到 3.1.0 版本以上！')
			console.log('App Launch')
		},
		onShow: function(){
			console.log('App Show')
		},
		onHide: function(){
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	@import url("./common/index.css");
	@import url("https://at.alicdn.com/t/font_2212024_kku4l2ttmxq.css");
	#ifdef
	uni-checkbox .uni-uni-checkbox-input {
		border-radius: 50% !important;
		color: #ffffff !important;
	}
	
	uni-checkbox .uni-checkbox-input.uni-checkbox-input-checked {
		width: 30rpx !important;
		height: 30rpx !important;
		color: #fff;
		background: #fff;
	}
	uni-checkbox .uni-checkbox-input.uni-checkbox-input-checked:before{
		font-size:30rpx !important;
	}
	.uni-checkbox-input.uni-checkbox-input-checked {
		/* border: none !important; */
		border-color:#adadad !important;
		/* border-radius: 0 !important; */
	}
	uni-checkbox .uni-checkbox-input{
		width: 30rpx !important;
		height: 30rpx !important;
		color: #fff;
		background: #fff;
		
	}
</style>
