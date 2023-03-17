<template>
  <div class="projects">
    <h1>Projects I've Worked On</h1>
    <div class="projectlink">
      <a href="https://hasspathways.com/">
        <img src="@/assets/hasspathways.png" width="512" />
      </a>
    </div>
  </div>
</template>

<style scoped>
h1 {
  text-align: center;
}

.projectlink {
  margin: auto;
  display: grid;
  text-align: center;
}

.projects img {
  margin: auto;
  filter: none;
  transition: 0.2s;
}

.projects img:hover {
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

