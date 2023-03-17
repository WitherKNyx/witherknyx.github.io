<template>
  <div class="games">
    <h1>Games I've Worked On</h1>
    <div class="gamelink">
      <a href="https://bennywoolbert.itch.io/waves">
        <img src="https://img.itch.zone/aW1nLzExMDYzMjE3LnBuZw==/original/v0wL4b.png" width="512" />
      </a>
    </div>
    <div class="gamelink">
      <a href="https://witherk.itch.io/chaos-colosseum">
        <img src="https://img.itch.zone/aW1nLzEwNzE1NjE0LnBuZw==/original/5yb0fM.png" width="512" />
      </a>
    </div>
    <div class="gamelink">
      <a href="https://witherk.itch.io/jiangshi-jump">
        <img src="https://img.itch.zone/aW1hZ2UvMTc2Mzk4Ni8xMDM5Njk1MS5wbmc=/original/DwxpLF.png" width="512" />
      </a>
    </div>
  </div>
</template>

<style scoped>
h1 {
  text-align: center;
}

.gamelink {
  display: grid;
  text-align: center;
}

.games img {
  filter: none;
  transition: 0.2s;
}

.games img:hover {
  opacity: 0.5;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
