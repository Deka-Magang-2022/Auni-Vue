<script setup lang="ts">
import { useStore } from '@/store';
const store = useStore();
	useHead({
		title: 'Array',
	});
store.out = [];
const simpanData = (value) => {
	store.input.push(value)
}
store.input = [];
let chars = [''];
let uniqueChars = [...new Set(chars)];

console.log(uniqueChars);

</script>

<template>
	<div>
		<div>
			{{ store.out }}
			<input enabled class="w-full rounded-md px-4 py-2 text-right" type="text" v-model="store.input">

		</div>
		<div v-for="(item, index) in store.input" :key="index">
			{{ item }}
		</div>
		<div>
			<button @click="simpanData(uniqueChars)" type="button"
				class="px-4 py-2 shadow dark:shadow-blue-500 bg-blue-500 rounded-md ml-3 text-white">Add</button>
		</div>

		<router-link :to="{ name: 'home' }" class="
				mt-5
				hover:text-gray-200
				dark:hover:text-gray-500
				hover:underline
			">{{ $t('pages.home') }}</router-link>
	</div>
</template>

<style scoped></style>

<route lang="yaml">
name: array
</route>
