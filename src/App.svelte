<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src={viteLogo} class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
    <a href="https://kahi-ui.nbn.dev/" target="_blank" rel="noreferrer">
      <img src='https://raw.githubusercontent.com/novacbn/kahi-ui/main/.assets/profile.png' class="logo kahi ui" alt="Kahi UI Logo" />
    </a>
  </div>
  <h1>Vite + Svelte + Kahi UI</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p>
    Check out <a href="https://kahi-ui.nbn.dev/" target="_blank" rel="noreferrer">Kahi UI</a>, an Easy to use Svelte UI for rapid prototyping
  </p>

  <p class="read-the-docs">
    Click on the Vite, Svelte and Kahi UI logos to learn more
  </p>
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
