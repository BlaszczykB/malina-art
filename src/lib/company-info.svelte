<div class="section-wrapper">
	<section class="content-sizing">
		<div>
			<h2>Malina Art</h2>
			<p>STUDIO MAKIJAŻU</p>
		</div>
		<img src="malwina.png" alt="Makeup example">
	</section>
</div>



<style>
	

	section {
		display: flex;
		align-items: center;
		justify-content: space-between;
	}

	.section-wrapper {
		background-color: var(--violet);
		padding: 5rem 0;
	}

	h2 {
		font-family: var(--fancy-font);
		color: #b97f34;
		font-size: 4rem;
		margin-bottom: 2rem;
	}

	p {
		font-size: 1.1rem;
		margin-bottom: 2rem;
	}

	img {
		border: 3px solid #b97f34;
		border-radius: 50%;
		max-width: 80vw;
	}

	@media (max-width: 768px) {
		section {
			flex-direction: column;
		}
	}
</style>