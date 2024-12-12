<template>
	<view>
		<up-text type="primary" text="我用十年青春,赴你最后之约"></up-text>
	</view>
</template>

<script lang="ts" name="user-center" setup>
	import { type Ref, ref } from "vue"

	let username : Ref<string> = ref("123")
</script>

<style lang="scss" scoped>

</style>