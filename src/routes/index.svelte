<script lang="ts">
	import Header from '$lib/Header.svelte';
	import Intro from '$lib/Intro.svelte';
	import LearnAboutFelt from '$lib/LearnAboutFelt.svelte';
	import WeAreLive from '$lib/WeAreLive.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<section>
	<Header>
		<h1>customizable communities that feel good</h1>
	</Header>
</section>
<section>
	<Intro />
</section>
<section>
	<LearnAboutFelt />
</section>
<section>
	<WeAreLive />
</section>
<section>
	<Footer />
</section>

<style>
	section {
		margin-bottom: 40px;
		max-width: 600px;
	}
</style>
