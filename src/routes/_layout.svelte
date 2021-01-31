<script>
	import Video from '../components/Video.svelte';

</script>

<style>
	main {
		width: 100vw;
		height: 100vh;
	}
</style>

<Video />

<main>
	<slot></slot>
</main>
