<script context="module">
	import { browser } from '$app/env'
	export async function load() {
		browser ? console.log('client') : console.log('ssr')
		return {}
	}
</script>
