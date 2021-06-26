<script>
	import { browser } from '$app/env'
	import { goto } from '$app/navigation'
  import { onMount } from 'svelte';

	if (browser) {
		setTimeout(function () {
					goto('/')
			}, 0)
	}
</script>
