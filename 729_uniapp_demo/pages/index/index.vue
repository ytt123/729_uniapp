<template>
	<view class="content">
		<!-- <image class="logo" src="/static/logo.png"></image> -->
		<view class="gr-y">
			<view class="gr-b100 gr-xyc gr-m10">
				<text class="gr-fontm20">1111</text>
			</view>
			<view class="gr-b100 gr-p10 gr-br10">
				<text class="gr-font20">222</text>
			</view>
		
			<view class="gr-btn">
				<view>123123123</view>
			</view>
			
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.title {
		font-size: 40rpx;
		// color: $gr-color-main
	}
	.itme {
		height: 200rpx;
		width: 200rpx;
		background-color: #4CD964;
		
	}

	.content {
		// display: flex;
		// flex-direction: column;
		// align-items: center;
		// justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	
</style>
