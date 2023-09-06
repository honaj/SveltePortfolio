<script lang="ts">
	import 'open-props/style'
	import 'open-props/normalize'
	import 'open-props/buttons'
	import Navbar from './navbar.svelte'
	import Footer from './footer.svelte'
</script>

<div>
	<Navbar/>
	<main>
		<slot/>
	</main>
</div>