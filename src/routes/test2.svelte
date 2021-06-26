<script>
	import { browser } from '$app/env'
	import { goto } from '$app/navigation'
  import { onMount } from 'svelte';

	onMount(async () => {
		if (browser) {
			goto('/')
		}
	})
</script>
