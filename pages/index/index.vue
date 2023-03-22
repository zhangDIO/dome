<template>
	<view class="">
		<swiper indicatorDots:true autoplay:true>
			<swiper-item><img :src="src" alt=""> </swiper-item>
			<swiper-item><img :src="src" alt=""> </swiper-item>
			<swiper-item><img :src="src" alt=""> </swiper-item>
			<swiper-item><img :src="src" alt=""> </swiper-item>


		</swiper>

	</view>
</template>

<script>
	export default {
		data() {
			return {
				src: 'https://img2.baidu.com/it/u=345670089,3951600800&fm=253&fmt=auto&app=138&f=JPEG?w=889&h=500'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>

</style>
