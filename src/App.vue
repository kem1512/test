<template>
	<div>
		<button @click="text = 'Hi'">click me {{ text }}</button>
	</div>
</template>

<script setup>
import { ref } from 'vue';

const text = ref("Hello World!")
</script>

<style scoped></style>