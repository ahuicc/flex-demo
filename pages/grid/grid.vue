
<template>	
	<view>
		<view class="grid">
			<view class="grid-cell">1/2</view>
			<view class="grid-cell">1/2</view>
		</view>
		<view class="grid">
			<view class="grid-cell">1/3</view>
			<view class="grid-cell">1/3</view>
			<view class="grid-cell">1/3</view>
		</view>
		<view class="grid">
			<view class="grid-cell1of6">1/6</view>
			<view class="grid-cell2of6">1/3</view>
			<view class="grid-cell3of6">1/2</view>
		</view>
	</view>
</template>
<style lang="scss" scoped>
	.grid{
		display: flex;
		.grid-cell{
			flex:1;
			height: 60rpx;
			line-height: 60rpx;
			background-color: #efefef;
			text-align: center;
			margin:10rpx 4rpx;
		}
		.grid-cell1of6{
			flex:1;
			height: 60rpx;
			line-height: 60rpx;
			background-color: #efefef;
			text-align: center;
			margin:10rpx 4rpx;
			
		}
		.grid-cell2of6{
			flex:2;
			height: 60rpx;
			line-height: 60rpx;
			background-color: #efefef;
			text-align: center;
			margin:10rpx 4rpx;
			
		}
		.grid-cell3of6{
			flex:3;
			height: 60rpx;
			line-height: 60rpx;
			background-color: #efefef;
			text-align: center;
			margin:10rpx 4rpx;
			
		}
	}

</style>
