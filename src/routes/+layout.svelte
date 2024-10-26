<script>
	import '../app.css';
	import FirstComponent from '$lib/components/FirstComponent.svelte';
	import SecondComponent from '$lib/components/SecondComponent.svelte';
	let { children } = $props();
</script>

{@render children()}
