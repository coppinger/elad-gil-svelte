<script>
	import '../app.css';
	import '@fontsource-variable/familjen-grotesk';
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
	class="min-w-screen mx-auto flex min-h-screen max-w-[1064px] flex-col gap-8 px-5 py-16 sm:px-8 sm:py-40"
>
	<slot></slot>
</div>
