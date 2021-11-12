<script>
	import Community from "./Community.svelte"
	import Distribute from "./Distribute.svelte"
	import Collab from "./Collab.svelte"
	import Funding from "./Funding.svelte"
	import HIW from "./HIW.svelte"
</script>

<main>
	<h1>Build your DevDAO</h1>
	<h3>git + p2p collab + funding = <a href="https://twitter.com/radicle" target="_blank">@radicle</a></h3>
	<form action="https://l57by8cmnip.typeform.com/to/zLsgh566" target="_blank">
		<input class="button" type="submit" value="Create DevDAO" />
	</form>
	<img class="heroimage" src="assets/images/org-page.png" alt="org page" />
	<Community />
	<Distribute />
	<Collab />
	<Funding />
	<HIW />
</main>

<style>
	main {
		padding: 2em;
		background-color:#18FF00;
		text-align: center;
	}
	h1 {
		color: white;
		font-size: 4em;
		font-weight: 700;
	}
	h3 {
		color: white;
		font-size: 2em;
	}
	a {
		color: white;
	}
	.heroimage {
		max-width: 100%;
	}

	.button {
		background-image: linear-gradient(to bottom right, #1AACF1, #5C54D6, #D340A8, #F44E5B, #FC7341);
		color: white;
		font-weight: 600;
		height: 60px;
		width: 180px;
		border-radius: 30px;
		border: 0;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
			padding: 4em;
		}
		h1 {
			font-size: 7em;
		}
	}
</style>
