<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view class="text-area ">
			<text class="title">{{title}}</text>
			<text class="gr-font13">{{title}}</text>

			<text class="ftm60">123123</text>


			<view class="gr-xyc itme">
				<text class="gr-font40">123123</text>
			</view>
			<view class="gr-xyc itme">
				<text class="gr-font13">123123</text>
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
	.itme {
		height: 200rpx;
		width: 200rpx;
		background-color: #4CD964;
	}

	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
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

	.title {
		font-size: 36rpx;
		color: $gr-color-main
	}
</style>
