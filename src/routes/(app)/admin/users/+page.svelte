<script>
	import { goto } from '$app/navigation';
	import { base } from '$app/paths';
	import { onMount } from 'svelte';

	onMount(async () => {
		await goto(`${base}/admin/users/overview`);
	});
</script>
