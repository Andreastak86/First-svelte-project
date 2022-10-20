<script>
 import Header from "./lib/Header.svelte"
  import Counter from './lib/Counter.svelte'
</script>

<header>
  <Header/>
</header>
<main>

  <h1>Vite + Svelte</h1>
  <h5>Like Ying and Yang</h5>

  <div class="card">
    <Counter />
  </div>

  <p>
    <!-- svelte-ignore security-anchor-rel-noreferrer -->
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>

<style>

 
  .read-the-docs {
    color: #888;
  }

  h1,h5 {
    color: red;
  }
</style>
