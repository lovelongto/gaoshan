<template>
	<view class="page">
		<view class="content">
			<h1>高山知音</h1>
			<h2>项目还在开发中</h2>
			消息
		</view>	
		<image class="box-image" src="../../../static/img/loading.jpg" mode="aspectFill"></image>	
	</view>
</template>

<script>
export default {
	data() {
		return {
			title: 'Hello'
		};
	},
	onLoad() {},
	methods: {}
};
</script>

<style>
	.box-image{
		position: fixed;
		top: 0;
		height: 100%;
		width: 100%
	}
	.page{
		height: 100%;
	}
.content {
	position: fixed;
	text-align: center;
	width: 100%;	
	height: 400upx;
	z-index: 9;
	margin-top: 200upx;
	/* background: image('../../../static/img/loading.jpg'); */
}
</style>
