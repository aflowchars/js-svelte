<script>
	import '../app.css';
	import { JavascriptLogo, SvelteLogo } from '$libs/icons';
</script>

<svelte:head>
	<title>Home &mdash; Aflowchars</title>
</svelte:head>

<main class="min-h-screen text-lg font-medium text-white">
	<section
		class="flex min-h-screen flex-col items-center justify-center bg-gradient-to-br from-orange-500 to-yellow-500"
	>
		<div
			class="container mx-auto flex max-w-screen-md -translate-y-1/2 flex-col items-center justify-center gap-8"
		>
			<div class="flex items-center gap-4">
				<JavascriptLogo class="h-20 w-20" />
				<SvelteLogo class="h-24 w-24" />
			</div>

			<h1 class="max-w-md text-center text-4xl font-semibold leading-normal text-white">
				Selamat datang di Svelte X Javascript
			</h1>
		</div>
		<slot />
	</section>
</main>
