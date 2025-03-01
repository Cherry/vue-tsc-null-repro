<template>
	{{ foo }}
</template>

<script setup lang="ts">
// more work would go here to handle v-model
defineProps({
	foo: {
		type: String,
		default: '',
	},
})
</script>
