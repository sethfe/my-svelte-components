<script>
  import FirstComponent from '$lib/components/FirstComponent.svelte';
</script>

<main class="flex flex-col items-center justify-center min-h-screen bg-slate-900 space-y-4">
<div class="flex flex-col items-center space-y-4 bg-slate-800 size p-20 rounded">
    <h1 class="flex text-3xl pb-4 font-bold text-white text-left">SvelteKit Button Component</h1>
  <FirstComponent state="primary">Login</FirstComponent>
  <FirstComponent state="success">Login</FirstComponent>
  <FirstComponent state="error">Login</FirstComponent>
  <FirstComponent state="disabled">Login</FirstComponent>
  </div>
</main>