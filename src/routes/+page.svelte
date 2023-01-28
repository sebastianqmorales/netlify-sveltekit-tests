<script>
	import '$lib/styles/app.css';
	import Header from '$lib/components/header.svelte';
	import CustomerSegment from '$lib/components/customersegment.svelte';
	import Features from '$lib/components/features.svelte';
	import Cta from '$lib/components/emailcta.svelte';
</script>

<Header />
<div class="container">
	<section class="section flipped-gradient mt-5">
		<Features />
	</section>
	<section class="section gradient mt-5">
		<CustomerSegment />
	</section>
	<Cta />
</div>

<!-- <form name="netlify-form-test" method="POST" netlify-honeypot="nbot-field" data-netlify="true">
	<input type="hidden" name="form-name" value="netlify-form-test" />
	<label for="name">Name</label>
	<input name="name" id="name" required placeholder="Name" type="text" />
	<label for="email">Email</label>
	<input name="email" id="email" required placeholder="Email" type="text" />
	<input type="submit" value="Submit" />
</form> -->
<style>
	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		row-gap: 40px;
	}
	.gradient {
		background: linear-gradient(180deg, rgba(255, 76, 0, 0.08) 0%, rgba(255, 255, 255, 0) 100%);
		width: 100%;
		padding-top: 50px;
	}

	.flipped-gradient {
		background: linear-gradient(180deg, rgba(217, 217, 217, 0) 0%, rgba(254, 123, 67, 0.15) 100%);
	}

	:root {
		--blur: 2.52px;
		--spread: -1.8px;
		--horiz: -1.43754px;
		--vert: 1.08327px;
	}
</style>
