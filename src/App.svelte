<script>
  import cosmosLogo from "./assets/cosmos.svg";
</script>

<main>
  <div>
    <a href="https://cloud.cosmosteam.org" target="_blank" rel="noreferrer">
      <img src={cosmosLogo} class="logo" alt="Cosmos Logo" />
    </a>
  </div>
</main>

<style>
  .logo {
    height: 14em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
    cursor: pointer;
  }
  .logo:hover {
    filter: drop-shadow(0 0 4em #ff3e00aa);
  }

  @media only screen and (max-width: 500px) {
    .logo {
      height: 8em;
      padding: 1.5em;
    }
  }
</style>
