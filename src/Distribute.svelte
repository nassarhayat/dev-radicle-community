<main>
	<h2>Code Distribution</h2>
	<h3>decentralise operational stack</h3>
	<div class="cardrow">
		<div class="card">
			<h3 class="cardtitle">Org</h3>
		</div>
		<div class="card">
			<h3 class="cardtitle">Pull/push</h3>
		</div>
		<div class="card">
			<h3 class="cardtitle">github/gitlab mirroring</h3>
		</div>
	</div>
</main>

<style>
	main {
		padding: 2em;
		background-color:#18FF00;
		text-align: center;
	}
	.card {
		background-color: white;
		min-height: 550px;
		border-radius: 30px;
	}
	.cardtitle {
		color: #E5E5E5;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
			padding: 4em;
		}
		.cardrow {
			display: grid;
			grid-template-columns: 1fr 1fr 1fr;
			gap: 30px;
		}
	}
</style>
