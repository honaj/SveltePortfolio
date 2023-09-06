<script lang="ts">
	import * as config from '$lib/config'
</script>

<nav>
	<a href='/' class='title'>
		<b>{config.title}</b>
	</a>
	<ul class='links'>
		<li>
			<a href='/about'>About</a>
		</li>
		<li>
			<a href='/projects'>Projects</a>
		</li>
	</ul>
</nav>


<style>
	nav {
			padding-block: var(--size-7);
	}
	
	.links {
			color: inherit;
			text-decoration: none;
			font-size: var(--font-size-6);
	}
	
	@media (min-width: 768px) {
			nav {
					display: flex;
					justify-content: space-between;
			}
			
			.links {
					display: flex;
					gap: var(--size-7);
					margin-block: 0;
			}
  }
</style>