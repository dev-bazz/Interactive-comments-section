<script lang="ts" setup>
	import Rating from ".././Rating/Rater.vue";
	defineProps({ msg: String });
</script>

<template>
	<div class="comment">
		<div class="rater">
			<Rating />
		</div>
		<div class="content">
			<h1>Comment {{ msg }}</h1>
		</div>
	</div>
</template>

<style scoped lang="scss">
	@use "./comment.scss" as *;
</style>
