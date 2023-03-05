<script lang="ts" setup>
	import { ref } from "vue";
	defineEmits(["upvote", "downvote"]);

	const rating = ref(0);
</script>

<template>
	<div class="rate-me">
		<button>+</button>
		<output>{{ rating }}</output>
		<button>-</button>
	</div>
</template>

<style lang="scss">
	@use "./rating.scss";
</style>
