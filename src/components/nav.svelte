<nav>
  <img src="icon.svg" alt="Garlic Bot Icon" />
  <span class="title">Garlic Bot</span>
  <div class="grow" />
  <a href="https://github.com/garlic-bot"><button>GitHub</button></a>
  <a href="https://discord.gg/t5Bs4cXfv2"><button>Support</button></a>
  <a
    href="https://discord.com/api/oauth2/authorize?client_id=954718378755489852&permissions=314432&scope=bot%20applications.commands"
    ><button>Invite</button></a
  >
</nav>

<style lang="scss">
  nav {
    height: 2.5rem;
    background-color: $col-bg-light;
    display: flex;
    flex-direction: row;
    align-items: center;

    img {
      height: 2rem;
      border-radius: 25%;
    }

    span {
      margin-left: 0.5rem;
      font-size: 1.5rem;
      font-weight: 500;
      color: $col-fg-primary;
    }

    button {
      height: 2.5rem;
      background-color: $col-bg-light;
      border: none;
      color: $col-fg-primary;
      padding: 0 0.5rem;
      font-size: 1em;
      cursor: pointer;
    }

    button:hover {
      background-color: $col-bg-lighter;
    }

    button:active {
      background-color: $col-bg-light;
    }
  }

  @media (min-width: 768px) {
    nav {
      padding: 0 4rem;
    }
  }
</style>
