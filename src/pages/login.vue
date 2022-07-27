<script setup lang="ts">
	useHead({
		title: 'Login',
	});
</script>

<template>
	<div class="bg-orange-200 -m-8">
		<div class="body-bg min-h-screen pt-12 md:pt-20 pb-6 px-2 md:px-0">
			<div class="max-w-lg mx-auto">
				<a href="#">
					<h1 class="text-4xl font-bold text-black text-center">Login</h1>
				</a>
			</div>

			<div class="bg-white max-w-lg mx-auto p-8 md:p-12 my-10 rounded-lg shadow-gray-300 shadow-2xl">
				<div>
					<p class="text-xl text-gray-600 pt-2">Sign in to your account.</p>
				</div>

				<div class="mt-10">
					<form class="flex flex-col" action="#">
						<div class="mb-6 pt-3 rounded">
							<label class="block text-sm font-bold mb-2 ml-3" for="">Username</label>
							<input type="text"
								class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-amber-900 transition duration-500 px-3 pb-3">
						</div>
						<div class="mb-6 pt-3 rounded ">
							<label class="block text-sm font-bold mb-2 ml-3" for="">Password</label>
							<input type="password"
								class="bg-gray-200 rounded w-full text-gray-700 focus:outline-none border-b-4 border-gray-300 focus:border-amber-900 transition duration-500 px-3 pb-3">
						</div>
						<div class="flex justify-end">
							<a href="#" class="text-sm text-amber-800 hover:text-amber-900 hover:underline mb-6">Forgot
								your
								password?</a>
						</div>
						<button
							class="bg-amber-800 hover:bg-amber-900 text-white font-bold py-2 rounded shadow-lg hover:shadow-xl transition duration-200"
							type="submit">Sign In</button>
					</form>
				</div>
			</div>

			<div class="max-w-lg mx-auto text-center mt-12 mb-6">
				<p class="text-black">Don't have an account? <a href="#" class="font-bold hover:underline">Sign up</a>.
				</p>
			</div>

			<footer class="max-w-lg mx-auto flex justify-center text-black">
				<router-link :to="{ name: 'home' }" class="
				dark:hover:text-gray-500
				hover:underline
			">{{ $t('pages.home') }}</router-link>
				<span class="mx-3">•</span>
				<a href="#" class="hover:underline">Privacy</a>
			</footer>
		</div>
	</div>
</template>

<style scoped></style>

<route lang="yaml">
name: login
</route>
