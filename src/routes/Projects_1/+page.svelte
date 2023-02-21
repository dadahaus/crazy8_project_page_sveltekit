<script>
	import Nav from './Nav.svelte';
</script>

<svelte:head>
	<title>first project section</title>
	<meta name="description" content="first" />
</svelte:head>
<Nav />
<h1 class="title">LOGOS</h1>
<section>
	<div class="name">
		<p>bacara</p>
	</div>
	<div class="specs">
		<p>
			Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nesciunt doloremque recusandae
			delectus, non ut odit, quas eum optio quasi tempora, cupiditate ab quod rerum! Quod inventore
			reprehenderit velit impedit tempora!
		</p>
	</div>
</section>
<main>
	<div class="image" />
	<!-- <img src="src/assets/1.png" alt="image" srcset="" /> -->
</main>

<style lang="scss">
	.title {
		text-align: center;
		padding: 0 0% 2% 0%;
	}
	section {
		display: flex;
		align-items: center;
		gap: 4rem;
		padding: 0 15% 7% 15%;

		& > * {
			display: flex;
		}
		.name {
			justify-content: center;
			flex-basis: 30%;
		}
		.specs {
			justify-content: flex-start;
			flex-basis: 70%;
			max-width: 40ch;
		}
	}

	main {
		// height: 70vh;
		// margin-top: -5%;
		display: flex;
		align-items: center;
		justify-content: center;
		// padding: 0 15%;
		.image {
			flex-basis: 50%;
			overflow: hidden;
			height: 70vw;
			// width: 70vw;
			// padding: 50%;
			background: center/ cover no-repeat url('src/assets/1.png');
		}
	}
</style>
