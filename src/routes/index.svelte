<svelte:head>
  <title>Home - Garlic Bot</title>
  <meta property="description" content="A bot for all your garlic trading and gamblind needs!" />
  <meta property="title" content="Home - Garlic Bot" />
  <meta property="og:thumbnail" content="https://garlic.vco.sh/icon.png" />
</svelte:head>

<div class="container">
  <div class="garlic-bot">
    <img src="icon.svg" alt="Garlic Bot Icon" />
    <div class="garlic-text">
      <h2>Garlic Bot</h2>
      <a
        href="https://discord.com/api/oauth2/authorize?client_id=954718378755489852&permissions=314432&scope=bot%20applications.commands"
      >
        <button>Add to Discord</button>
      </a>
    </div>
  </div>
</div>

<style lang="scss">
  .container {
    padding: 2rem 20%;
    text-align: center;

    .garlic-bot {
      margin-top: 4rem;

      img {
        border-radius: 100%;
        height: 10rem;
      }

      h2 {
        font-size: 4rem;
        font-weight: 500;
        color: $col-fg-primary;
        margin: 0;
      }

      button {
        margin-top: 1rem;
        padding: 0.5rem 1rem;
        border: none;
        border-radius: 0.5rem;
        font-weight: 500;
        font-size: 2rem;
        cursor: pointer;
        background-color: $col-bg-cta;
        color: $col-fg-primary;
      }

      button:hover {
        background-color: $col-bg-cta-hover;
      }

      button:active {
        background-color: $col-bg-cta;
      }
    }
  }

  @media (max-width: 768px) {
    .container {
      padding: 1rem 2%;
    }
  }
</style>
