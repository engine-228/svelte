<svelte:options tag="my-app"/>

<script>
	import { onMount } from 'svelte';

	export let wasCreated;

	onMount(() => {
		wasCreated = true;
	});
</script>
