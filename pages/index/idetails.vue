<template>
	<view>
		<view>
			<Idetails></Idetails>
		</view>
	</view>
</template>

<script>
	import Idetails from '@/components/iindex/idetails.vue'
	export default {
		components: {
			Idetails,
		},
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

<style>
</style>
