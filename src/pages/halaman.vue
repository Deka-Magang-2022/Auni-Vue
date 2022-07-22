<script setup lang="ts">
	useHead({
		title: 'halaman',
	});
import Sv1 from '@/assets/img/sv2.png';
import Sv2 from '@/assets/img/sv1.png';
import Sv3 from '@/assets/img/sv3.png';
import Sv4 from '@/assets/img/sv4.png';
import Sv5 from '@/assets/img/sv5.png';
import Sv6 from '@/assets/img/sv6.png';
import Sv7 from '@/assets/img/sv7.png';
import Sv8 from '@/assets/img/sv8.png';
import Sv9 from '@/assets/img/sv9.png';

</script>

<template>
	<div>
		<!-- <div class="grid grid-row-2 grid-cols-3 bg-black">
		<div class="col-span-2 min-h-screen bg-red-500" >
			1
		</div>
		<div class=" h-1/2 bg-gray-700">
			2
		</div>
			<div class="h-1/2 bg-yellow-500">
				3
			</div>
	</div> -->
		<div class="grid grid-cols-3 grid-rows-5 min-h-screen grid-flow-col">
			<div class="col-span-2 row-span-5 bg-[#f2cf77]">
				<nav class=" flex  items-center text-[#005564] bg-[#f2cf77]  ">
					<div class=" font-serif font-bold flex items-center h-full">
						<a href="" class="my-5 mr-72 mx-16 uppercase text-2xl">shave</a>
						<div>
							<a class="mx-5" href=""> How It Wors </a>
						</div>
						<div>
							<a class="mx-5" href=""> product </a>
						</div>
						<div>
							<a class="mx-5" href=""> gifts </a>
						</div>
						<div>
							<a class="mx-5" href=""> Join Today </a>
						</div>
					</div>
				</nav>
				<div class="bg-[#f2cf77]  min-h-screen ">
					<div class="m-16">
						<p
							class="flex leading-snug tracking-wider text-6xl  font-medium  text-[#005564] font-serif text-left">
							The ultimate app that help you find
							the righ high-quality blade for your face</p>
					</div>
					<div class=" transition ease-in-out delay-150 w-auto hover:-translate-y-1 hover:scale-110  duration-300 ">
						<a class="hover:bg-[#3aa7aa] py-4 font-semibold  mx-16 uppercase text-xl font-serif text-[#f2cf77] bg-[#005564] px-24"
							href="">get started</a>
					</div>
					<div class="flex justify-end h-72 px32"><img :src="Sv1" width=""></div>
				</div>
			</div>
			<div
				class="row-span-2  flex justify-center leading-tight tracking-wider  font-serif text-xl text-white bg-[#d66674]">
				<div class=" mx-24 ">
					<p class=" my-8  text-center  ">
						We have high-quality goomming gift for everyone.
						you'll find gift sets, giftcards, and more!
					</p>
					<div
						class=" transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 hover:bg-[#3aa7aa] duration-300  p-2 my-8 mb-20 text-[#003851] bg-[#93dbde] ">
						<a href="" class=" flex justify-center  uppercase">shop the gift sets</a>
					</div>
				</div>
			</div>
			<div class="row-span-3 grid grid-cols-3 grid-rows-3  bg-yellow-500 col-span-2">
				<div class=" flex justify-center  bg-[#ffdcec] "><img :src="Sv1" width=""></div>
				<div class=" flex justify-center  bg-[#93dbde] "><img :src="Sv2" width=""></div>
				<div class=" flex justify-center  bg-[#ffb0d0] "><img :src="Sv3" width=""></div>
				<div class=" flex justify-center  bg-[#c0e6c5] "><img :src="Sv4" width=""></div>
				<div class=" flex justify-center  bg-[#fb8b98] "><img :src="Sv5" width=""></div>
				<div class=" flex justify-center  bg-[#c2ebed] "><img :src="Sv6" width=""></div>
				<div class=" flex justify-center  bg-[#ffdcec] "><img :src="Sv7" width=""></div>
				<div class=" flex justify-center  bg-[#93dbde] "><img :src="Sv8" width=""></div>
				<div class=" flex justify-center  bg-[#fee797] "><img :src="Sv9" width=""></div>
			</div>
		</div>
	</div>
	<div class="bg-[#d66674]  right-0">
		<img class="min-w-screen "
			src="https://cdn.discordapp.com/attachments/989028955585675292/999128321285697606/Vector.png" alt="">
	</div>
	<!-- <nav class="   items-center w-2/3 text-[#005564] bg-[#f2cf77]  ">
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

	</div> -->
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
