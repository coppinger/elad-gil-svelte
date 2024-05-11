<script>
	import '../app.css';
	import '@fontsource-variable/familjen-grotesk';
	import { isNew } from '$lib/store';
</script>

<svelte:head>
	<!-- Primary Meta Tags -->
	<title>Elad Gil</title>
	<!-- Add a favicon -->
	<link rel="icon" type="image/jpeg" href="./elad-gil.jpg" />
	<meta name="title" content="Elad Gil" />
	<meta
		name="description"
		content="I am a technology entrepreneur, investor, and future forward optimist. I 
have been working on a series of investments, incubations, and operating 
companies focused on the technology future."
	/>

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://eladgil.com/" />
	<meta property="og:title" content="Elad Gil" />
	<meta
		property="og:description"
		content="I am a technology entrepreneur, investor, and future forward optimist. I 
have been working on a series of investments, incubations, and operating 
companies focused on the technology future."
	/>
	<meta property="og:image" content="./elad-gil.jpg" />

	<!-- Twitter -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://eladgil.com/" />
	<meta property="twitter:title" content="Elad Gil" />
	<meta
		property="twitter:description"
		content="I am a technology entrepreneur, investor, and future forward optimist. I 
have been working on a series of investments, incubations, and operating 
companies focused on the technology future."
	/>
	<meta property="twitter:image" content="./elad-gil.jpg" />
</svelte:head>

<div
	class="min-w-screen relative mx-auto flex min-h-screen max-w-[1064px] flex-col gap-8 px-5 py-16 sm:px-8 sm:py-40"
>
	{#if $isNew}
		<div
			class="absolute left-0 top-0 -z-10 grid h-full w-full grid-cols-5 border border-dashed border-neutral-300"
		>
			<div class="h-full w-full border-r border-dashed border-neutral-300"></div>
			<div class="h-full w-full border-r border-dashed border-neutral-300"></div>
			<div class="h-full w-full border-r border-dashed border-neutral-300"></div>
			<div class="h-full w-full border-r border-dashed border-neutral-300"></div>
		</div>
	{/if}
	<button
		on:click={() => isNew.set(!$isNew)}
		class="fixed bottom-0 left-0 mx-auto flex w-full items-center justify-center gap-2 border-t border-neutral-300 bg-opacity-50 py-8 text-xl backdrop-blur-3xl"
		>Toggle tweaks <svg
			width="24"
			height="24"
			viewBox="0 0 24 24"
			fill="none"
			xmlns="http://www.w3.org/2000/svg"
		>
			<path
				d="M16.5879 7.41207L16.588 7.41216C16.705 7.52919 16.8949 7.52932 17.0122 7.41207L18.6121 5.81217C18.6121 5.81215 18.6121 5.81213 18.6122 5.81211C18.7292 5.69494 18.7292 5.50502 18.6122 5.38787C18.6122 5.38784 18.6121 5.38781 18.6121 5.38778M16.5879 7.41207L18.6121 5.38778M16.5879 7.41207C16.4707 7.29493 16.4707 7.10503 16.5879 6.98786L16.5879 6.98782L18.1877 5.38788M16.5879 7.41207L18.1877 5.38788M18.6121 5.38778C18.4949 5.27069 18.305 5.2707 18.1878 5.38784M18.6121 5.38778L18.1878 5.38784M18.1878 5.38784C18.1878 5.38785 18.1877 5.38786 18.1877 5.38787C18.1877 5.38787 18.1877 5.38788 18.1877 5.38788M18.1878 5.38784L18.1877 5.38788M4.21205 20.2121L4.21208 20.2121L15.4121 9.01213C15.4121 9.01212 15.4121 9.01211 15.4121 9.0121C15.5292 8.89495 15.5292 8.70499 15.4121 8.58784C15.4121 8.58783 15.4121 8.58782 15.4121 8.58781M4.21205 20.2121L14.6343 8.23428C14.9467 7.92187 15.4532 7.92187 15.7657 8.23428L15.4121 8.58781M4.21205 20.2121C4.0949 20.3293 3.90501 20.3293 3.78786 20.2121L3.78777 20.212C3.67073 20.095 3.6706 19.9051 3.78786 19.7878M4.21205 20.2121L3.78786 19.7878M15.4121 8.58781C15.2949 8.47068 15.105 8.47069 14.9878 8.58784L3.78786 19.7878M15.4121 8.58781L3.78786 19.7878M20.96 2.25998H21.46V1.75998V0.799974C21.46 0.722664 21.5226 0.659973 21.6 0.659973C21.6773 0.659973 21.74 0.722664 21.74 0.799974V1.75998V2.25998H22.24H23.2C23.2773 2.25998 23.34 2.32267 23.34 2.39998C23.34 2.47729 23.2773 2.53998 23.2 2.53998H22.24H21.74V3.03998V3.99998C21.74 4.07729 21.6773 4.13998 21.6 4.13998C21.5226 4.13998 21.46 4.07729 21.46 3.99998V3.03998V2.53998H20.96H20C19.9226 2.53998 19.86 2.47729 19.86 2.39998C19.86 2.32267 19.9226 2.25998 20 2.25998H20.96ZM21.74 9.75998V10.26H22.24H23.2C23.2773 10.26 23.34 10.3227 23.34 10.4C23.34 10.4773 23.2773 10.54 23.2 10.54H22.24H21.74V11.04V12C21.74 12.0773 21.6773 12.14 21.6 12.14C21.5226 12.14 21.46 12.0773 21.46 12V11.04V10.54H20.96H20C19.9226 10.54 19.86 10.4773 19.86 10.4C19.86 10.3227 19.9226 10.26 20 10.26H20.96H21.46V9.75998V8.79998C21.46 8.72267 21.5226 8.65998 21.6 8.65998C21.6773 8.65998 21.74 8.72267 21.74 8.79998V9.75998ZM12.96 2.25998H13.46V1.75998V0.799974C13.46 0.722648 13.5227 0.659973 13.6 0.659973C13.6773 0.659973 13.74 0.722656 13.74 0.799974V1.75998V2.25998H14.24H15.2C15.2773 2.25998 15.34 2.32266 15.34 2.39998C15.34 2.47729 15.2773 2.53998 15.2 2.53998H14.24H13.74V3.03998V3.99998C13.74 4.07729 13.6773 4.13998 13.6 4.13998C13.5227 4.13998 13.46 4.0773 13.46 3.99998V3.03998V2.53998H12.96H12C11.9227 2.53998 11.86 2.4773 11.86 2.39998C11.86 2.32265 11.9227 2.25998 12 2.25998H12.96Z"
				fill="#171717"
				stroke="#171717"
			/>
		</svg>
	</button>
	<slot></slot>
</div>
