<script setup lang="ts">
	import { useStore } from '@/store';
	import VitailseLogo from '@/assets/logo.png';
	import Userimg from '@/assets/profil.jpg';
	useHead({
		title: 'Vitailse | Opinionated vite starter template',
	});

	const store = useStore();
	const { t } = useI18n();
</script>

<template>
	<div class="grid place-items-center min-h-[80vh]">
		<div
			class="grid text-amber-900 bg-orange-200 dark:bg-neutral-500/40  py-10 px-10  shadow-2xl dark:shadow-purple-500 rounded max-w-lg text-center place-items-center  dark:text-purple-400 outline outline-amber-900 dark:outline-purple-600 ">
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
					<p> No telp/WA : <a href="https://wa.me/+6282116852441" target="_blank"
							class="after:content-['_↗']  dark:text-purple-600 dark:hover:text-sky-200 font-bold">0821-1685-2441</a>
					</p>
					<p> Email : <a href="mailto:aunifikri@gmail.com" target="_blank"
							class="after:content-['_↗']  dark:text-purple-600 dark:hover:text-sky-200 font-bold">aunifikri@gmail.com</a>
					</p>
					<p> Instagram : <a href="https://www.instagram.com/aunivz.16_/" target="_blank"
							class="after:content-['_↗']  dark:text-purple-600 dark:hover:text-sky-200 font-bold">aunivz.16_</a>
					</p>
					<a href="https://github.com/AuniVz" target="_blank"
						class="after:content-['_↗']  dark:text-purple-600 dark:hover:text-sky-200 font-bold">Github</a>
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
					<p>- <a class="after:content-['_↗'] dark:text-purple-600 hover:text-sky-200 font-semibold"
							target="_blank"
							href="https://www.google.co.id/maps/place/SD+MUHAMMADIYAH+2/@-0.4906311,117.1413606,15z/data=!4m5!3m4!1s0x0:0x363ac7fe27edcd6d!8m2!3d-0.4973719!4d117.1341062">
							SD Muahmmadiyah 2 SAMARINDA</a></p>
					<p>- <a class="after:content-['_↗'] dark:text-purple-600 hover:text-sky-200 font-semibold"
							target="_blank"
							href="https://www.google.co.id/maps/place/SMP+Negeri+16+Samarinda/@-0.5146555,117.13044,11.95z/data=!4m5!3m4!1s0x2df67fd303b28c2b:0x65e7eeb487ccff3e!8m2!3d-0.5315734!4d117.0907694">
							SPMN 16 SAMARINDA </a></p>
					<p>- <a class="after:content-['_↗']  dark:text-purple-600 hover:text-sky-200 font-semibold"
							target="_blank"
							href="https://www.google.co.id/maps/place/SMKTI+Airlangga/@-0.5146555,117.13044,11.95z/data=!4m5!3m4!1s0x2df67f1489bfeb63:0xe1ef6869246e2125!8m2!3d-0.4851223!4d117.1484416">
							SMK TI Airlangga SAMARINDA </a></p>
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
			<div class="grid grid-cols-4 grid-flow gap-2">
				<div
					class="bg-amber-900 hover:outline-amber-900 hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<a href="todo-list"> Todo List </a>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900 hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'kalkulator1' }">Kalkulator
					</router-link>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900  hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'jurnal' }">Jurnal
					</router-link>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900  hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'login' }">Login
					</router-link>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900  hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'halaman' }">Halaman
					</router-link>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900  hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'rng' }">
						RNG
					</router-link>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900  hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'color-switcher' }">
						Color
					</router-link>
				</div>
				<div
					class="bg-amber-900 hover:outline-amber-900  hover:bg-black dark:hover:outline dark:hover:bg-white dark:bg-green-500 dark:text-purple-700 px-4 py-2 rounded-md text-orange-300">
					<router-link :to="{ name: 'netflix' }">
						Netflix
					</router-link>
				</div>
			</div>
		</div>
	</div>
</template>

<route lang="yaml">
name: home
</route>
