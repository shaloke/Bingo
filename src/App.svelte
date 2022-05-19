<script>
  import logo from "./assets/svelte.png";
  import Counter from "./lib/Counter.svelte";
  let alt = 'Svelte Logo'
  let h1 = 'Bingo!'
</script>

<main>
  <img src='http://xjc.vin/backageground/logo.png' alt={alt} />
  <h1>{h1}!</h1>
  <p>{h1}~你的随身科研助手</p>  
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
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
    color: #845EC2;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  p {
    font-weight: bold;
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
    color: #429949;
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
