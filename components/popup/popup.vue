<template>
	<view>

    </view>
</template>

<script>
	export default {
        name:"popup",
		data() {
			return {
				title: 'Hello'
			}
		},
        props:{
            // 开启动画
			animation: {
				type: Boolean,
				default: true
			},
			// 弹出层类型，可选值，top: 顶部弹出层；bottom：底部弹出层；center：全屏弹出层
			type: {
				type: String,
				default: 'center'
			},
			// 是否开启自定义
			custom: {
				type: Boolean,
				default: false
			},
			// maskClick
			maskClick: {
				type: Boolean,
				default: true
			},
			show: {
				type: Boolean,
				default: true
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
