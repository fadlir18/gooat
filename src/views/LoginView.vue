<template>
	<div id="Login">
		<div class="w-full p-6 flex justify-center items-center">
			<div class="w-full max-w-xs">
				<div class="bg-black p-8 shadow rounded mb-6">
					<h1 class="
				mb-6
				text-lg
				text-gray-100
				font-thin">You dope beats issa waiting you</h1>

					<div class="mb-4">
						<label class="
					blockuppercase
					tracking-wide
					text-xs
					font-bold
					mb-2
					text-gray-100
					">
							First Name
						</label>

						<input type="text" class="
					appearance-none
					block
					w-full
					bg-white
					text-gray-700
					border
					border-gray-400
					rounded
					py-3
					px-4
					leading-tight
					focus:outline-none
					focus:bg-white
					focus:border-gray-500
					">
					</div>
					<span class="text-red-500">
						This is an error message
					</span>

					<button class="
					block
					w-full
					bg-green-500
					text-white
					rounded-sm
					py-3
					text-sm
					tracking-wide
					" type="submit">
						Login
					</button>

				</div>
				<p class="text-center text-md text-gray-900">
					Don't have an account yet?
					<router-link to="register" class="text-blue-500 no-underline hover:underline">
						Register
					</router-link>
				</p>
			</div>
		</div>
	</div>
</template>