<template>
	<div>
		<button @click="text = 123">click me {{ text }}</button>
	</div>
</template>

<script setup>
import { ref } from 'vue';

const text = ref("Hello World!")
</script>