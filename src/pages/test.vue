<script setup lang="ts">
	useHead({
		title: 'test',
	});
</script>

<template>
	<div class="background -m-8 w-screen z-10">
		<div class=" grid gap-2 h-screen">
			<div class="h-screen bg-gradient-to-b from-black via-black/10 to-black/90 bg-local">
				<nav class=" w-full text-white pt-5  px-14 flex items-center ">
					<div class="font-bold  text-red-600 text-4xl">Netflix</div>
					<div class=" ml-auto flex items-center h-full">
						<select id="language" class="py-1 border-white bg-black ">
							<option value="">English</option>
							<option value="">indonesia</option>
						</select>
						<div class=" px-4 py-1 font-[arial] m-5 rounded after: bg-red-600 ">
							<a class=" " href=" #">Sign In</a>
						</div>
					</div>
				</nav>
				<div class="text-white mt-14 py-20 px-auto text-center ">
					<p class="text-5xl font-bold ">Unlimited movies, TV <br> shows, and more.</p>
					<p class="text-2xl my-4 ">Watch anywhere. Cancel anytime.</p>
					<p class="text-xl py-3">Ready to watch? Enter your email to create or restart your membership.</p>
					<form class="w-auto h-[60px] " action="">
						<input placeholder="Email address" class="h-full w-[450px] " type="text">
						<button class=" h-full w-[213px] text-2xl bg-red-600">Get Started > </button>
					</form>

					<div>

					</div>
				</div>
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
	</div>
</template>

<style scoped>
body,
html {
	height: 100%;
}
.background {
	height: 100%;
		width: 100%;

		position: absolute;
		top: 1;
		/* z-index: ; */
		background-color: black;
		background-image: url('./src/assets/img/bg.jpg');
		/* Full height */
		/* Center and scale the image nicely */
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
		}
</style>

<route lang="yaml">
name: test
</route>
