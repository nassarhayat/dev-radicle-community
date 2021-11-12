<main>
	<h2>Support + Funding</h2>
	<h3>funded agreements -> streamed funds</h3>
	<div class="cardrow">
		<div class="card">
			<h3 class="cardtitle">grant RFP + proposals</h3>
		</div>
		<div class="card">
			<h3 class="cardtitle">funded contributor</h3>
		</div>
		<div class="card">
			<h3 class="cardtitle">funded issues</h3>
		</div>
	</div>
</main>

<style>
	main {
		padding: 2em;
		background-color:#18FF00;
		text-align: center;
	}
	h2 {
		color: white;
		font-size: 4em;
		font-weight: 700;
	}
	h3 {
		color: white;
		font-size: 2em;
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
		h2 {
			font-size: 5em;
		}
		.cardrow {
			display: grid;
			grid-template-columns: 1fr 1fr 1fr;
			gap: 30px;
		}
	}
</style>
