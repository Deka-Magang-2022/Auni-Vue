<script setup lang="ts">
import { useStore } from '@/store';
const store = useStore()
	useHead({
		title: 'kalkulator1',
	});
	store.input = 'text 1'
	// store.input = store.input + 'text 2'
	store.input += 'text 2'
	store.temp = ''




</script>

<template>
	<div>
		<div class="border rounded-md p-5 border-black max-w-lg ">
			<div class="">
				<div>
				{{ store.input }}
				</div>
			</div>
		</div>
		<router-link
			:to="{ name: 'home' }"
			class="
				mt-5
				hover:text-gray-200
				dark:hover:text-gray-500
				hover:underline
			"
			>{{ $t('pages.home') }}</router-link
		>
	</div>
</template>

<style scoped></style>

<route lang="yaml">
name: kalkulator1
</route>
