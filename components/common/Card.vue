<template>
	<view class="card">
		<view >-</view>
		<view class="card-name">{{cardTitle}}</view>
		<view >-</view>
	</view>
</template>

<script>
	export default{
		props:{
			cardTitle:String
		}
	}
</script>

<style scoped>
	.card{
		padding: 20rpx 0;
		display: flex;
		justify-content: center;
		font-weight: 700;
	}
	.card-name{
		padding: 0 20rpx;
		font-size: 32rpx;
	}
</style>