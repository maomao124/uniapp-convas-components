<template>
	<view>
		<web-view src="https://www.bilibili.com/" @loaded="loadWeb"></web-view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			loadWeb(e)
			{
				console.log('加载完成',e);
			}
		}
	}
</script>

<style>

</style>
