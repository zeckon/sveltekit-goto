<script>	
	import { goto } from '$app/navigation'  

</script>
<svelte:window on:sveltekit:start={goto('/')}/>