<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>

<template>
	<div>
		<button @click="counter.increment">
			click me to count up {{ counter.count }}
		</button>
	</div>
</template>

<style scoped></style>
