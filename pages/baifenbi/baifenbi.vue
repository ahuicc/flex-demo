<template>
	<view>
		<view class="grid">
			<view class="grid-cell" grid-full>full</view>
		</view>
		<view class="grid">
			<view class="grid-cell grid-cell-half" >1/2</view>
			<view class="grid-cell">auto</view>
			<view class="grid-cell">auto</view>
		</view>
		<view class="grid">
			<view class="grid-cell grid-cell-4of" >1/4</view>
			<view class="grid-cell">auto</view>
			<view class="grid-cell grid-cell-3of">1/3</view>
		</view>
		
	</view>
</template>

<style lang="scss" scoped>
	.grid{
		display: flex;
		.grid-cell{
			flex: 1;
			height: 60rpx;
			line-height: 60rpx;
			text-align: center;
			margin: 10rpx 4rpx;
			background-color: #efefef;
		}
		.grid-full{
			flex: 0 0 100%;
		}
		.grid-cell-half{
			flex:0 0 50%;
		}
		.grid-cell-4of{
			flex:0 0 25%;
		}
		.grid-cell-3of{
			flex: 0 0 33.3333%;
		}
	}

</style>
