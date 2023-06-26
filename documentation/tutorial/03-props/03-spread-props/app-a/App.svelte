<script>
	import Info from './Info.svelte';

	const pkg = {
		name: 'svelte',
		version: 4,
		speed: 'blazing',
		website: 'https://svelte.dev'
	};
</script>

<Info name={pkg.name} version={pkg.version} speed={pkg.speed} website={pkg.website} />
