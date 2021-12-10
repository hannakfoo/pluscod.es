<script>
  // import logo from './assets/svelte.png'
  // import Counter from './lib/Counter.svelte'
</script>

<main>
  <h1>+ pluscod.es</h1>
  <p>This is a project a made in <a href="https://dusty.domains/">dustydomains</a> campagne by Netlify.</p>
</main>

<style>
  :root {
    font-family: 'IBM Plex Sans', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }
  h1 {
    color: yellow;
    text-transform: uppercase;
    font-size: 2rem;
    font-weight: 300;
    line-height: 1.1;
    margin: 2rem auto;
  }
  a{
    text-decoration: underline;
    color:yellow;
    font-weight: bold;
  }

  p {
    max-width: 14rem;
    color: yellow;
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
