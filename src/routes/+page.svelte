<script>
	import TextSection from '$lib/components/TextSection.svelte';
</script>

<div class="flex flex-col gap-16 sm:flex-row">
	<h1 class="hidden whitespace-nowrap text-4xl sm:block md:text-5xl">Elad Gil</h1>
	<div class="flex flex-col gap-4">
		<div class="flex flex-col gap-4 sm:flex-row sm:items-center">
			<img
				src="./elad-gil.jpg"
				alt="avatar"
				class="
            h-48
            w-48
            sm:h-7
            sm:w-7"
			/>
			<div class="flex flex-col">
				<h1 class="block text-3xl sm:hidden">Elad Gil</h1>
				<div class="flex">
					<p>(</p>
					<ul class="flex">
						<li>
							<a
								href="https://twitter.com/eladgil"
								target="_blank"
								class="text-neutral-500 underline">Twitter</a
							>
						</li>
						<li>,&nbsp;</li>
						<li>
							<a href="https://blog.eladgil.com/" target="_blank" class="text-neutral-500 underline"
								>Writing</a
							>
						</li>
						<li>,&nbsp;</li>
						<li>
							<a
								href="https://growth.eladgil.com/"
								target="_blank"
								class="text-neutral-500 underline">Book</a
							>
						</li>
					</ul>
					<p>)</p>
				</div>
			</div>
		</div>
		<h2 class="text-lg font-bold">Technology entrepreneur, investor, & future forward optimist</h2>
	</div>
</div>
<main class="flex flex-col gap-4">
	<p class="italic">
		I have been working on a series of investments, incubations, and operating companies focused on
		the technology future.
	</p>

	<h3>Entrepreneurship & running companies.</h3>

	<ul>
		<li class="">Started two companies (Mixerlabs - bought by Twitter - and Color Health)</li>

		<li class="">
			Recently incubated / helped start <a href="">Braintrust</a>, an AI eval (and more!) company
		</li>

		<li class="">
			Was a VP at Twitter (which bought a startup where I was CEO) and worked on AI & mobile at
			Google
		</li>
	</ul>

	<p>
		I also wrote the best-selling <a href="" class="font-bold">High Growth Handbook</a> - about
		scaling companies & tactical advice for post-product market fit (hiring execs, broadening
		product lines, M&A, sales, HR issues, fundraises etc). You can buy the book on
		<a href="">Amazon</a>
		or <a href="">read for free online</a>
	</p>

	<TextSection title="Investing.">Past investments include:</TextSection>

	<p class="non-ul list-item">
		Airbnb, Airtable, Anduril, Applied Intuition, Brex, Checkr, Coinbase, dbt Labs, Deel, Figma,
		Flexport, Gitlab, Gusto, Instacart, Navan, Notion, Opendoor, PagerDuty, Pinterest, Retool,
		Rippling, Samsara, Square, Stripe etc
	</p>
	<TextSection title="AI.">I got involved with ML & generative AI early.</TextSection>

	<ul class="list-disc">
		<li class="">
			I invested early in, or led rounds for e.g. Braintrust, Character, Harvey, Mistral,
			Perplexity, Pika, and others
		</li>

		<li class="">I prior ran AI centric product orgs at Google & Twitter</li>

		<li class="">I have an AI podcast named No Priors</li>
	</ul>

	<TextSection title="Longevity.">
		I have degrees in Math and Biology (including a PhD from MIT) and have seen existence proofs of <a
			href="">life extension in organisms due to gene knockouts</a
		>.
	</TextSection>

	<ul class="">
		<li class="">I personally identified a<a href="">gene involved in lifespan</a></li>
		<li class="">
			I have also funded a clinical trial at Stanford on aging (it didnt work! DOH! Happy to try
			again)
		</li>
		<li class="">
			Involved with anti-aging biotech companies (<a href="">BioAge</a> and
			<a href="">NewLimit</a>). BioAge now has an interesting <a href="">drug for muscle</a>.
		</li>
	</ul>

	<TextSection title="Beauty & inspiration.">
		Thinking about society-level beauty and inspirations at Monumental (coming soon!). Why don’t we
		build massive inspiring monuments and art projects anymore that can inspire people to do amazing
		things? Belief in progress is reflective.</TextSection
	>

	<TextSection title="Human capital movements."
		>The drain from key parts of society of smart, young, high conviction people is starting to show
		its impact. Am interested in projects to encourage really smart people to work in societally
		important fields which currently lack smart people.</TextSection
	>

	<TextSection title="Projects I need help with:">
		Monumental (coming soon!), a chain of new K-12 schools inspired by ancient Greece, two new
		foundation models I want to exist.
	</TextSection>
</main>
<footer class="flex flex-col gap-4">
	<TextSection title="Where you can find me.">
		<ul class="flex gap-0">
			<li>
				<a href="https://twitter.com/eladgil" target="_blank" class="text-neutral-500 underline"
					>Twitter</a
				>
			</li>
			<li>,&nbsp;</li>
			<li>
				<a href="https://blog.eladgil.com/" target="_blank" class="text-neutral-500 underline"
					>Writing</a
				>
			</li>
			<li>,&nbsp;</li>
			<li>
				<a href="https://growth.eladgil.com/" target="_blank" class="text-neutral-500 underline"
					>Book</a
				>
			</li>
		</ul>
	</TextSection>

	<TextSection title="Media assets."
		>Download an official headshot of me <a href="">here</a></TextSection
	>
</footer>
