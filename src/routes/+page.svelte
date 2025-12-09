<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import IntroSection from '$lib/components/IntroSection.svelte';
	import DarkSection from '$lib/components/DarkSection.svelte';
	import InvisibleApproach from '$lib/components/InvisibleApproach.svelte';
	import Progress from '$lib/components/Progress.svelte';
	import ScientificEvidence from '$lib/components/ScientificEvidence.svelte';
	import PeopleTouch from '$lib/components/PeopleTouch.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Header />

<main>
	<Hero />
	<IntroSection />
	<DarkSection />
	<InvisibleApproach />
	<Progress />
	<ScientificEvidence />
	<PeopleTouch />
</main>

<Footer />

