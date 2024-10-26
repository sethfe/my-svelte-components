<script>
  import FirstComponent from '$lib/components/FirstComponent.svelte';
  import SecondComponent from '$lib/components/SecondComponent.svelte';
</script>

<main class="min-h-screen bg-slate-900 text-white font-sans">
  <header class="bg-slate-800 py-6 shadow-md">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-bold">My Svelte Components</h2>
    </div>
  </header>

  <section class="container mx-auto my-12 px-4">
    <div class="flex flex-col items-center bg-slate-800 p-12 rounded-lg shadow-lg w-full max-w-lg mx-auto">
      <h2 class="text-3xl font-bold mb-6">SvelteKit Button Component Showcase</h2>
      <div class="grid grid-cols-2 gap-4 w-full">
        <FirstComponent state="primary">Primary</FirstComponent>
        <FirstComponent state="success">Success</FirstComponent>
        <FirstComponent state="error">Error</FirstComponent>
        <FirstComponent state="disabled">Disabled</FirstComponent>
      </div>
    </div>
  </section>

  <section class="container mx-auto my-12 px-4">
    <div class="flex flex-col items-center bg-slate-800 p-12 rounded-lg shadow-lg w-full max-w-md mx-auto">
      <h2 class="text-3xl font-bold mb-6 text-center">Login to Your Account</h2>
      <SecondComponent />
    </div>
  </section>


</main>