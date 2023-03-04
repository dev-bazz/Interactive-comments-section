<script setup>
	import Comment from "./components/Comment.vue";
	import { ref } from "vue"; // Vue3 Dependencies
	const hello = ref("hello World");
</script>

<template>
	<h1>Hello World</h1>
	<Comment msg="By BaZz" />
</template>
