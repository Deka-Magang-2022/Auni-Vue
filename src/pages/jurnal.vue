<script setup lang="ts">
import Markdown from '@/assets/markdown.md';
import Bulan1 from '@/assets/bulan1.md';

useHead({
	title: 'jurnal',
});
</script>

<template>
	<div>
		<div class="my-10 prose border border-black rounded-md p-10">
			<Markdown />
		</div>
		<div class="my-10 prose border border-black rounded-md p-10">
			<Bulan1 />
		</div>
		<router-link :to="{ name: 'home' }" class="
				mt-5
				hover:text-gray-200
				dark:hover:text-gray-500
				hover:underline
			">{{ $t('pages.home') }}</router-link>
	</div>
</template>

<style scoped>
</style>

<route lang="yaml">
name: jurnal
</route>
