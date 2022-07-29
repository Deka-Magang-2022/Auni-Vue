<script setup lang="ts">
import Img1 from '@/assets/img/net1.png';
import Img2 from '@/assets/img/net2.png';
import Img3 from '@/assets/img/net3.jpg';
import Img4 from '@/assets/img/net4.png';
	import Bg from "@/assets/img/bg.jpg";
	useHead({
		title: 'Netflix',
	});

</script>

<template>
	<div class=" -m-8  bg-cover h-screen"
		style="background-image: url('https://user-images.githubusercontent.com/33485020/108069438-5ee79d80-7089-11eb-8264-08fdda7e0d11.jpg')">
		<div class=" grid gap-2 h-screen">
			<div class="h-screen bg-gradient-to-b from-black via-black/10 to-black/90 bg-local">
				<nav class=" w-full text-white pt-5  px-14 flex items-center ">
					<div class="font-bold  text-red-600 text-4xl">Netflix</div>
					<div class=" ml-auto flex items-center h-full">
						<select id="language" class="py-1 border-white bg-black ">
							<option value="">English</option>
							<option value="">indonesia</option>
						</select>
						<div class=" px-4 py-1 mx-5 font-[arial]  h-[34px] rounded after: bg-[#e20813] ">
							<a class=" " href=" #">Sign In</a>
						</div>
					</div>
				</nav>
				<div class="text-white mt-14 py-20 px-auto text-center ">
					<p class="text-5xl font-bold ">Unlimited movies, TV <br> shows, and more.</p>
					<p class="text-2xl my-4 ">Watch anywhere. Cancel anytime.</p>
					<section>
						<div>
							<p class="text-xl py-3">Ready to watch? Enter your email to create or restart your
								membership.</p>
							<form class="w-full h-[60px] " action="">
								<input placeholder="Email address" class="h-full w-[450px] " type="text">
								<button class=" h-full w-[213px] text-2xl font-[arial] bg-[#e20813]">Get Started >
								</button>
							</form>
						</div>
					</section>
				</div>
			</div>
			<div class="grid grid-row-6 gap-2  bg-gray-700">
				<div class="bg-black h-[477px] flex">
					<section>
						<h1 class="text-white text-left text-5xl font-bold ml-20 pt-14 pb-10 mt-20">Enjoy on your TV.
						</h1>
						<h2 class="text-white text-left text-2xl font-[arial] ml-20 ">Watch on Smart TVs, Playstation,
							Xbox,
							<br> Chromecast, Apple TV, Blu-ray players, and
							<br> more.
						</h2>

					</section>
					<img class="ml-48 w-[400px] h-96 mt-1" :src="Img1">

				</div>
				<div class="bg-black h-[460px] flex">
					<img class="ml-1 w-[500px] h-96 mt-1 mr-20" :src="Img2">
					<section>
						<h1 class="text-white text-left text-5xl font-bold ml-20 pt-14 pb-10 mt-20">Download your shows
							<br> to watch offline.
						</h1>
						<h2 class="text-white text-left text-2xl font-[arial] ml-20">Save your favorites easily and
							always have <br> something to watch.
						</h2>
					</section>
				</div>
				<div class="bg-black h-[535px] flex">
					<section>
						<h1 class="text-white text-left text-5xl font-bold ml-20 pt-14 pb-10 mt-32">Watch everywhere.
						</h1>
						<h2 class="text-white text-left text-2xl font-[arial] ml-20">Stream unlimited movies and TV
							shows on <br> your phone, tablet, laptop, and TV.
						</h2>
					</section>

					<img class="ml-32 w-[500px] h-96 mt-20 mr-20" :src="Img3">
				</div>
				<div class="bg-black h-[525px] flex">
					<img class="ml-10 w-[500px] h-96 mt-20 mr-10" :src="Img4">
					<section>
						<h1 class="text-white text-left text-5xl font-bold ml-20 pt-14 pb-10 mt-32">Create profiles for
							<br> kids.
						</h1>
						<h2 class="text-white text-left text-2xl font-[arial] ml-20">Send kids on adventures with their
							favorite <br> characters in a space made just for them—free <br> with your membership.
						</h2>
					</section>
				</div>
				<div class="bg-black h-[970px]  ">
					<h1 class="text-white font-bold text-5xl mt-20 text-center">Frequently Asked Questions</h1>
					<div class="text-left flex place-content-center">
						<div class="flex flex-col place-items-start mt-16 gap-2 text-white">
							<div>
								<p
									class="border-2  bg-[#303030] border-[#303030] w-[750px] h-[70px] p-5 font-[arial] text-2xl">
									What Is Netflix?</p>
							</div>
							<div>
								<p
									class="border-2  bg-[#303030] border-[#303030] w-[750px] h-[70px] p-5 font-[arial] text-2xl">
									How much does Netflix cost?</p>
							</div>
							<div>
								<p
									class="border-2  bg-[#303030] border-[#303030] w-[750px] h-[70px] p-5 font-[arial] text-2xl">
									Where can I wach?</p>
							</div>
							<div>
								<p
									class="border-2  bg-[#303030] border-[#303030] w-[750px] h-[70px] p-5 font-[arial] text-2xl">
									How do I cancel?</p>
							</div>
							<div>
								<p
									class="border-2  bg-[#303030] border-[#303030] w-[750px] h-[70px] p-5 font-[arial] text-2xl">
									What can I watch on Netflix?</p>
							</div>
							<div>
								<p
									class="border-2  bg-[#303030] border-[#303030] w-[750px] h-[70px] p-5 font-[arial] text-2xl">
									Is Netflix good for kids?</p>
							</div>
						</div>
					</div>
					<div class="text-white my-20 text-center">
						<p class="text-xl  py-3">Ready to watch? Enter your email to create or restart your membership.
						</p>
						<form class="w-full h-[60px] " action="">
							<input placeholder="Email address" class="h-16 w-[450px] " type="text">
							<button class=" h-16 w-[213px] text-2xl font-[arial] bg-[#e20813]">Get Started >
							</button>
						</form>
					</div>
				</div>
				<div class="bg-black h-[426px] px-64 pt-[70px] text-gray-700">
					<div class="mb-8">
						<p>Questions? Call <a href="">007-803-321-2130</a></p>
					</div>
					<div class="grid grid-cols-4 grid-rows-4 gap-4">
						<p> FAQ </p>
						<p>Help Center</p>
						<p>Account</p>
						<p>Media Center</p>
						<p>Investor Relations</p>
						<p>Jobs</p>
						<p>Redeem Gift Cards</p>
						<p>Buy Gift Cards</p>
						<p>Ways to Watch</p>
						<p>Terms of Use</p>
						<p>Privacy</p>
						<p>Cookie Preferences</p>
						<p>Corporate Information</p>
						<p>Contact Us</p>
						<p>Speed Test</p>
						<p>Legal Notices</p>
						<p>Only on Netflix</p>
					</div>
					<div class="pt-5 ">
						<select name="" id="" class="py-1 border-gray-700 bg-black">
							<option value="">English</option>
							<option value="">Indonesia</option>
						</select>
					</div>
					<div class="py-6">
						<p>Netflix Indonesia</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
</style>
<route lang="yaml">
name: netflix
</route>
