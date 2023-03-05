<script lang="ts" setup>
	defineProps({ msg: String });
</script>

<template>
	<h1 class="comment">Comment {{ msg }}</h1>
</template>

<style scoped lang="scss">
	@use "./comment.scss" as *;
</style>
