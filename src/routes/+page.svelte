<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<script>
  import { goto } from '$app/navigation';
</script>

<button on:click={() => goto('/about')}>
  Aller sur la page À propos
</button>
