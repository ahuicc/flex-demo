<template>
	<view class="parent">
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
		<view class="child"></view>
	</view>
</template>

<style lang="scss" scoped>
	.parent{
		width: 100%;
		background-color: black;
		display: flex;
		flex-flow:row wrap;
		align-content: flex-start;
		.child{
			box-sizing: border-box;
			background-color: white;
			flex:0 0 25%;
			height: 100rpx;
			border:1px solid red;
		}
	}

</style>
