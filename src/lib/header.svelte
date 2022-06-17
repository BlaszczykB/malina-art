<header>
	<div class="image-wrapper">
		<img class="logo" src="logo.svg" alt="logo" />
	</div>
	<div class="navigation-wrapper">
		<nav class="content-sizing">
			<a href="/">Home</a>
			<a href="/about">About</a>
			<a href="/gallery">Gallery</a>
			<a href="/contact">Contact</a>
		</nav>
	</div>
</header>

<style>

	.logo {
		width: 15rem;
	}
	.navigation-wrapper {
		padding: 1rem;
		border-top: 2px solid #b97f34;
		border-bottom: 2px solid #b97f34;
		background-color: white;
	}
	.image-wrapper {
		display: flex;
		justify-content: center;
		background-color: var(--pink-100);
		/* background-color: #d3919066; */
	}

	nav {
		display: flex;
		justify-content: space-between;
	}

	a {
		text-decoration: none;
		color: black;
		font-size: 1.3rem;
		font-weight: 600;
	}

	a:hover {
		color: #b97f34;
	}
</style>
