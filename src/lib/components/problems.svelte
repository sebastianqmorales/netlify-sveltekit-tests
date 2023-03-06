<script>
	import Typewriter from 'svelte-typewriter';
	import creator from '$lib/icons/creator.svg';
	import user from '$lib/icons/user.svg';
	import handshake1 from '$lib/icons/hand-shake-1.svg';
	import { text } from 'svelte/internal';

	const textArray = [
		'monetization',
		'what content gets promoted or hidden',
		'the cut of the profits',
		'your data and who it is sold to',
		'your voice and who is allowed to speak'
	];
</script>

<div class="container my-6">
	<div class="content">
		<div class="feature-text">
			<h1>What's the problem?</h1>
			<h5 class="thirdtext mt-6">Social media companies have too much power.</h5>

			<div class="flex-container">
				<div class="text">
					Platforms like Twitter, YouTube and most others have too much control over the platform.
				</div>
				<div class="text">
					They have complete control over the monetization of content, including: how many ads we
					have to watch what content gets promoted or hidden the cut of the profits that goes to
					content creators
				</div>
				<div>
					The companies only want money, so they incentivize creating content that gets the most ad
					views—clickbait garbage that users don't actually enjoy because the platforms just want us
					to scroll or click the next video, and watch another ad.
				</div>
				<div>
					We're sick of it. So we're giving the power back to the users, because we love the
					creators and hate the ads.
				</div>
			</div>
			<!-- <h3>Power over how many ads we watch</h3>
			<h3>Power over what content gets promoted or hidden</h3>
			<h3>Power over the cut of the profits</h3>
			<h3>Power over your data and who it is sold to</h3>
			<h3>Power over your voice and who is allowed to speak</h3> -->
		</div>
	</div>
</div>

<style>
	.flex-container {
		display: flex;
		flex-direction: column;
		gap: 2rem;
		padding-left: 20%;
		padding-right: 20%;
		justify-content: center;
	}

	.flex-container > div {
		font-weight: 500;
	}
	.grid-container {
		display: grid;
		grid-template-columns: repeat(1, auto);
		row-gap: 2rem;
	}
	.graphic {
		width: 100px;
		height: auto;
	}
	/* .smaller {
		width: 70px;
		height: auto;
		padding: 12px;
	} */
	.feature-text {
		text-align: center;
		margin-bottom: 7rem;
	}
	.feature-text > h1 {
		color: #ff4d00;
	}
	.thirdtext {
		padding-left: 20%;
		padding-right: 20%;
		line-height: 2rem;
		/* color: #fe7b43; */
		font-weight: 500;
	}

	.content > h4 {
		color: #ff4d00;
	}
</style>
