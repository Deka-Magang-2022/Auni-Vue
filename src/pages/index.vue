<script setup lang="ts">
	import { useStore } from '@/store';
	import VitailseLogo from '@/assets/logo.png';
	import Userimg from '@/assets/profil.jpg';
	import Markdown from '@/assets/markdown.md';
	useHead({
		title: 'Vitailse | Opinionated vite starter template',
	});

	const store = useStore();
	const { t } = useI18n();
</script>

<template>
	<div class="grid place-items-center min-h-[80vh]">
		<div class="grid bg-orange-200 dark:bg-neutral-500/40  py-10 px-10  shadow-2xl dark:shadow-purple-500 rounded max-w-lg text-center place-items-center  dark:text-purple-400 outline outline-amber-900 dark:outline-purple-600 ">
			<div class="grid max-w-lg text-center  rounded-full place-items-center">
				<img :src="Userimg" width="300"
					class=" outline-double outline-amber-900 dark:outline-green-600 outline-offset-4 dark:shadow-green-500 shadow-xl rounded-full mx-auto" />
			</div>
			<h1 class="uppercase font-bold text-xl mt-10">profil</h1>
			<div class="text-sm text-justify ">
				<p> Nama : Khairul Auni Fikri </p>
				<p> Date Of Birth: Samarinda,16 jan 2005 </p>
				<p> Religion : Islam </p>
				<p> Gender : Male </p>
			</div>
			<div class="grid max-w-lg text-center place-items-center mt-10">
				<h1 class="uppercase font-bold text-xl">Contact</h1>
				<div class="text-sm text-justify ">
					<p> No telp/WA : 0821 1685 2441 </p>
					<p> Email : aunifikri@gmail.com</p>
					<p> Instagram : aunivz.16_ </p>
				</div>
			</div>
			<div class="max-w-lg text-center mt-10">
				<h1 class="uppercase font-bold text-xl">Hobby</h1>
				<div class="text-sm text-justify">
					<p>- Game</p>
					<p>- Automotive</p>
					<p>- Music</p>
					<p>- Internet</p>
				</div>
			</div>
			<div class="max-w-lg text-center mt-10">
				<h1 class="uppercase font-bold text-xl">Education</h1>
				<div class="text-sm text-justify">
					<p>- SD Muhammadiyah 2 Samarinda</p>
					<p>- SMPN 16 Samarinda</p>
					<p>- SMK TI AirLangga Samarinda</p>
				</div>
			</div>
			<div class="max-w-lg text-center mt-10">
				<h1 class="uppercase font-bold text-xl">Skill</h1>
				<div class="text-sm text-justify">
					<p> - Laravel Framework PHP</p>
					<p> - css</p>
					<p> - html</p>
					<p> - Javascript</p>
				</div>
			</div>
			<div class="max-w-lg py-10 text-center mt-10">
				<h1 class="uppercase font-bold text-xl">About</h1>
				<p class="text-sm text-justify"> Siswa Ti yang antusia dan bermotivasi tinggi dengan kemampuan
					Programming dan mencari tantangan baru</p>
			</div>
			<div
				class="bg-amber-900 hover:outline-amber-900 hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-3 py-1 rounded-md text-orange-300">
				<a href="todo-list"> Next> </a>
			</div>
		</div>
	</div>
</template>

<route lang="yaml">
name: home
</route>
