<script>
	import { onMount } from 'svelte';
    import { PUBLIC_BASE_URL } from '$env/static/public'

	let photos = [];

	onMount(async () => {
		const res = await fetch(`${PUBLIC_BASE_URL}/`);
		photos = await res.json();
        console.log({
            photos
        })
	});
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
