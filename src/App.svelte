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
		<input class="button" type="submit" value="Apply to join beta" />
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
	a {
		color: white;
	}
	.heroimage {
		max-width: 100%;
	}

	.button {
		background-color:black;
		color: white;
		font-weight: 600;
		height: 100px;
		width: 80%;
		border: 0;
		position: fixed;
		bottom:0%;
	}
	input {
		font-size: 1.5em;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
			padding: 4em;
		}
		.button {
			width: 400px;
		}
	}
</style>
