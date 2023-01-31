<template>
	<view class="container">
		
		<view class="intro">这是首页</view>
		<button type="primary" @click="Go" >跳转</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			Go(){
				uni.navigateTo({
					url: "/pages/sub/index"
				})
			}
		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
	.intro{
		text-align: center;
		margin-bottom: 15rpx;
	}
</style>
