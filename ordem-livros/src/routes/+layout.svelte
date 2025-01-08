<script lang="ts">
	import '../app.css';
  import Logo from '../components/template/Logo.svelte';
	let { children } = $props();
</script>

<div class="flex flex-col justify-center items-center bg-black text-white min-h-screen">

	<Logo/>

{@render children()}
</div>


