<script>
	import { browser } from '$app/env'
	import { goto } from '$app/navigation'  

	if (browser) {
		setTimeout(function () {
					goto('/')
			}, 0)
	}
</script>
