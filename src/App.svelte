<script>
  // import logo from './assets/svelte.png'
  // import Counter from './lib/Counter.svelte'
</script>

<main>
  <h1>+ pluscod.es</h1>

  <!-- <Counter /> -->
</main>

<style>
  :root {
    font-family: 'Catamaran', sans-serif;
font-family: 'IBM Plex Sans', sans-serif;
  }


  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1 {
    color: yellow;
    text-transform: uppercase;
    font-size: 2rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  }
</style>
