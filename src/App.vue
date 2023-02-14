<template>
	<div class="home">
		<h1>{{ title }}</h1>
		<el-button>按钮</el-button>
	</div>
</template>

<script setup>
	import { ref } from "vue";

	const title = ref("vue");
</script>

<style lang="scss" scoped>
	@import "./style.scss";
</style>
