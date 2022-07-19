<script setup lang="ts">
	useHead({
		title: '404. Not Found',
	});
	const { t } = useI18n();
</script>

<template>
	<h1 class="text-blue-500 font-extrabold flex flex-col text-center">
		<span class="text-7xl">goblok.</span>
		<span class="text-5xl mt-5">
			gpp tetap semangat !!!
			<!-- {{ t('pages.not-found') }} -->
			</span>
	</h1>
</template>

<route lang="yaml">
name : not-found
meta:
    layout: 404
</route>
