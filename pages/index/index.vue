<template>
	<view class="container">
		<view class="first-face face">
			<view class="pip"></view>
		</view>
		<view class="second-face face">
			<view class="pip"></view>
			<view class="pip second-face-pip-2"></view>
		</view>
		<view class="third-face face">
			<view class="pip"></view>
			<view class="pip third-face-pip-2"></view>
			<view class="pip third-face-pip-3"></view>
		</view>
		<view class="fourth-face face">
			<view class="fourth-face-column">
				<view class="pip"></view>
				<view class="pip"></view>
			</view>
			<view class="fourth-face-column">
				<view class="pip"></view>
				<view class="pip"></view>
			</view>
		</view>
		<view class="fifth-face face">
			<view class="fifth-face-column">
				<view class="pip"></view>
				<view class="pip"></view>
			</view>
			<view class="fifth-face-column  fifth-face-column-2">
				<view class="pip"></view>
			</view>
			<view class="fifth-face-column">
				<view class="pip"></view>
				<view class="pip"></view>
			</view>
		</view>
		<view class="sixth-face face">
			<view class="six-face-column">
				<view class="pip"></view>
				<view class="pip"></view>
				<view class="pip"></view>
			</view>
			<view class="six-face-column">
				<view class="pip"></view>
				<view class="pip"></view>
				<view class="pip"></view>
			</view>
		</view>
	</view>
</template>
<script>
	export default {
		dara() {
			return {
				count: 99
			}
		}
	}
</script>

<style scoped lang="scss">
	.container {
		display: flex;
		justify-content: center;
		align-items: center;
		vertical-align: center;
		flex-wrap: wrap;
		align-content: center;
		font-family: 'Open Sans', sans-serif;
		background: linear-gradient(top, #222, #333);
		background-color: skyblue;
		
		.first-face{
			display: flex;
			justify-content: center;
			align-items: center;
		}
		.second-face{
			display: flex;
			justify-content: space-between;
			.second-face-pip-2{
				align-self: flex-end;
			}

		}
		.third-face{
			display: flex;
			justify-content: space-between;
			.third-face-pip-2{
				align-self: center;
			}
			.third-face-pip-3{
				align-self: flex-end;
			}
		}
		
		.fourth-face,.sixth-face{
			display: flex;
			justify-content: space-between;
			.fourth-face-column{
				display: flex;
				flex-direction: column;
				justify-content: space-between;
			}
		}
		.fifth-face{
			display: flex;
			justify-content: space-between;
			.fifth-face-column{
				display: flex;
				flex-direction: column;
				justify-content: space-between;
			}
			.fifth-face-column-2{
				justify-content: center;	
				background-color: red;
				
			}
		}
	.pip{
		display: flex;
		width: 48rpx;
		height: 48rpx;
		border-radius: 50%;
		margin: 8rpx;
		
		background-color: #333;
		box-shadow: inset 0 6rpx #111,inset 0 -6rpx #555;
	}
	}

	.face {
		margin: 32rpx;
		padding: 8rpx;

		background-color: #e7e7e7;
		width: 208rpx;
		height: 208rpx;
		object-fit: contain;

		box-shadow: inset 0 10rpx white, inset 0 -10rpx #bbb, inset 10rpx 0 #d7d7d7, inset -10rpx 0 #d7d7d7;
		border-radius: 20%;

	}
</style>