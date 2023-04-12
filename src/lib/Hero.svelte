<script>
	import { fade, scale } from 'svelte/transition';
</script>

<section class="py-10 bg-white">
	<div class="px-6 mx-auto max-w-7xl">
		<div class="w-full mx-auto text-left md:w-11/12 xl:w-9/12 md:text-center">
			<h1
				in:scale
				class="mb-8 text-4xl font-extrabold leading-none tracking-normal text-gray-900 md:text-6xl md:tracking-tight"
			>
				<span>We</span>
				<span
					class="block w-full py-2 text-transparent bg-clip-text leading-12 bg-gradient-to-r from-green-400 to-green-800 lg:inline"
					>Build, Grow and Manage</span
				> <span>360 Aspects of Your Brand.</span>
			</h1>
			<h3
				class="mb-8 text-xl font-extrabold leading-none tracking-normal text-gray-900 md:text-xl md:tracking-tight"
			>
				<span>Your Search For </span>
				<span
					class="block w-full py-2 text-transparent bg-clip-text leading-12 bg-gradient-to-r from-green-700 to-green-700 lg:inline"
					>Marketplace ​Management Service</span
				> <span> Ends Here!!</span>
			</h3>

			<a
				href="/contact"
				class="inline-flex items-center justify-center w-full px-6 py-3 mb-2 text-xl text-white bg-green-500 rounded-2xl sm:w-auto sm:mb-0 transition ease-in hover:scale-105 hover:bg-green-600"
			>
				Book A Free Audit
				<svg
					class="w-4 h-4 ml-1"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 20 20"
					fill="currentColor"
					><path
						fill-rule="evenodd"
						d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
						clip-rule="evenodd"
					/></svg
				>
			</a>
		</div>

		<div class="max-w-lg mx-auto my-10 text-center">
			<div class="relative z-0 w-full mt-8">
				<div class="relative overflow-hidden rounded-xl shadow-2xl">
					<div class="flex items-center flex-none px-4 bg-green-400 rounded-b-none h-11 rounded-xl">
						<div class="flex space-x-1.5">
							<div class="w-3 h-3 border-2 border-white rounded-full" />
							<div class="w-3 h-3 border-2 border-white rounded-full" />
							<div class="w-3 h-3 border-2 border-white rounded-full" />
						</div>
					</div>
					<img transition:fade src="hero.png" alt="Amazon growth chart" />
				</div>
			</div>
		</div>
	</div>
</section>
