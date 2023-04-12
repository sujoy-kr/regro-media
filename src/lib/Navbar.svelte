<script>
	let showMenu = false;

	function toggleNavbar() {
		showMenu = !showMenu;
	}
</script>

<div class="sticky top-0 z-30 w-full w-100 bg-white shadow-mdF">
	<div class="bg-white">
		<nav class="container px-6 py-4 mx-auto md:flex md:justify-between md:items-center">
			<div class="flex items-center justify-between">
				<a class="text-xl font-bold text-green-700 md:text-2xl hover:text-blue-400" href="/">
					<img src="logo.png" alt="Regro Media" class="w-28" />
				</a>
				<!-- Mobile menu button -->
				<div on:click={toggleNavbar} class="flex md:hidden">
					<button
						type="button"
						class="text-green-700 hover:text-green-500 focus:outline-none focus:text-green-500"
					>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke-width="1.5"
							stroke="currentColor"
							class="w-6 h-6"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
							/>
						</svg>
					</button>
				</div>
			</div>

			<!-- Mobile Menu open: "block", Menu closed: "hidden" -->
			<div
				class="flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0 {showMenu
					? 'flex'
					: 'hidden'}"
			>
				<a class="hover:text-green-600 transition ease-in text-lg" href="/">Home</a>
				<a class="hover:text-green-600 transition ease-in text-lg" href="/case-studies"
					>Case Studies</a
				>

				<a class="hover:text-green-600 transition ease-in text-lg" href="/services">Services</a>
				<div class="space-y-2">
					<a
						href="/contact"
						class="transition ease-in hover:scale-105 py-3 px-6 text-center hover:bg-green-600 inline-flex items-center justify-center w-full px-6 py-3 mb-2 text-lg text-white bg-green-500 rounded-2xl sm:w-auto sm:mb-0"
					>
						Contact
					</a>
				</div>
			</div>
		</nav>
	</div>
</div>
