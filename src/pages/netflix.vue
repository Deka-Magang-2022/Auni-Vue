<script setup lang="ts">
	import Bg from "@/assets/img/bg.jpg";
	useHead({
		title: 'Netflix',
	});
</script>

<template>
	<div class="-m-8 grid gap-2 bg-gray-500 h-screen">
		<div class="min-h-screen bg-local"  >

		</div>
		<div class="grid grid-row-6 gap-2  bg-gray-700">
			<div class="bg-black h-[477px]">
				1
			</div>
			<div class="bg-black h-[460px]">
				2
			</div>
			<div class="bg-black h-[535px]">3</div>
			<div class="bg-black h-[525px]">4</div>
			<div class="bg-black h-[970px] ">5</div>
			<div class="bg-black h-[426px] ">6</div>
		</div>
	</div>
</template>

<style scoped></style>

<route lang="yaml">
name: netflix
</route>
