<script>
	import { page } from '$app/stores';
</script>

<nav>
	<ul>
		<a class="left_nav" href="/"><h5>previous</h5></a>
		<a class="center_nav" href="/"><h5>back</h5></a>
		<a class="right_nav" href="http://"><h5>next</h5></a>
	</ul>
</nav>

<style lang="scss">
	nav {
		padding: 2rem 5rem 2rem 5rem;
		text-transform: uppercase;
		ul {
			display: flex;
			align-items: center;
			justify-content: space-between;
			gap: 5rem;
			text-transform: uppercase;
			& > * {
				display: flex;
				justify-content: center;
				font-weight: 100;
			}

			.left_nav {
			}

			.center_nav {
			}

			.right_nav {
			}
		}
	}
</style>
