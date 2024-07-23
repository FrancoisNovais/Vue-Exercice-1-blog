<template>
  <footer>
    <p>
      Made with <a href="https://vuejs.org/">Vue</a> by
      <a href="https://github.com/FrancoisNovais">François</a>
    </p>
  </footer>
</template>

<style scoped>
footer {
  display: flex;
  align-items: center;
  justify-content: center;
  border-top: 3px solid var(--yellow);
  height: var(--footer-height);
}
a {
  text-decoration: none;
  color: var(--yellow);
}
</style>
