
<div class="section-wrapper">
	<section class="content-sizing">
		<div>
			<h2>O Mnie</h2>
			<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ipsum pariatur dolores saepe corporis labore repellat eveniet vel nemo ad ratione odio minima voluptas velit, alias dolorum animi quos praesentium consequatur blanditiis, enim vitae quo amet. Et, rem! Porro pariatur inventore ab ducimus placeat a. Quasi officia expedita hic recusandae animi!</p>
		</div>
		<img src="malwina.png" alt="Malwina Stanula">
	</section>
</div>



<style>
	section {
		display: flex;
		align-items: center;
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
		max-width: 80vw;
		border: 3px solid var(--gold);
		border-radius: 50%;
	}

	.section-wrapper {
		padding: 5rem 0;
		background-color: var(--main-background-color);
	}

	@media (max-width: 768px) {
		section {
			flex-direction: column;
		}
	}
</style>
