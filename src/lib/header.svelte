<header>
	<div class="image-wrapper">
		<img class="logo" src="logo.svg" alt="logo" />
	</div>
	<div class="navigation-wrapper bordered">
		<nav class="content-sizing">
			<a href="/">Strona Główna</a>
			<!-- <a href="/about">About</a> -->
			<a href="/gallery">Galeria</a>
			<a href="/contact">Kontakt</a>
		</nav>
	</div>
</header>

<style>

	.logo {
		height: var(--logo-size);
	}
	.navigation-wrapper {
		padding: var(--padding-small) 0;
		background-color: white;
		height: 26px;
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
