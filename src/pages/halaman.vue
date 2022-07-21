<script setup lang="ts">
	useHead({
		title: 'halaman',
	});
</script>

<template>
	<nav class="   items-center w-2/3 text-[#005564] bg-[#f2cf77]  ">
		<div class=" flex items-center h-full">
			<h1 class="my-5 w-1/3 mx-16 font-bold uppercase text-xl">shave</h1>
			<div>
				<a class="font-serif font-bold mx-5" href=""> How It Wors </a>
			</div>
			<div>
				<a class="font-serif font-bold mx-5" href=""> product </a>
			</div>
			<div>
				<a class="font-serif font-bold mx-5" href=""> gifts </a>
			</div>
			<div>
				<a class="font-serif font-bold mx-5" href=""> Join Today </a>
			</div>
		</div>
	</nav>
	<div class="bg-[#f2cf77] w-2/3 min-h-screen ">
		<div class="">
			<h3
				class="flex mx-16 leading-tight tracking-wider text-5xl w-2/3 font-medium mb-8 text-[#005564] font-serif justify-start">
				The ultimate app that help you find
				the righ high-quality blade for your face</h3>
		</div>
		<div>
			<a class="py-4 font-semibold  mx-16 my-28 uppercase text-xl font-serif text-[#f2cf77] bg-[#005564] px-24"
				href="">get started</a>
		</div>
	</div>
	<div class="bg-[#d66674]  right-0">
		<img class="min-w-screen "
			src="https://cdn.discordapp.com/attachments/989028955585675292/999128321285697606/Vector.png" alt="">

	</div>
	<div
		class="absolute  top-[66px] h-2/4  w-1/3 text-white  leading-tight tracking-wider font-serif text-lg right-0 bg-red-500 ">
		<h3 class=" m-16 flex justify-center ">
		We have high-quality goomming gift for everyone.
		you'll find gift sets, giftcards, and more!
		</h3>
	</div>
	<div class="absolute  top-[365px] h-[367px]  w-1/3 right-0 bg-blue-500 ">
		<img class=" " src="https://cdn.discordapp.com/attachments/989028955585675292/999128321285697606/Vector.png"
			alt="">

	</div>
	<!-- <router-link :to="{ name: 'home' }" class="
				mt-5
				hover:text-gray-200
				dark:hover:text-gray-500
				hover:underline
			">{{ $t('pages.home') }}</router-link> -->
</template>

<style scoped></style>

<route lang="yaml">
name: halaman
</route>
