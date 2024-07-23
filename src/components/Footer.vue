<template>
  <footer>
    <div class="container">
      <p>Made with Vue by <a href="https://github.com/FrancoisNovais">François</a></p>
    </div>
  </footer>
</template>

<style scoped>
footer {
  display: flex;
  align-items: center;
  padding: 20px 0;
  border-top: 3px solid var(--main-yellow);
  position: absolute;
  bottom: 0;
  width: 100%;
}
a {
  text-decoration: none;
  color: var(--main-yellow);
}
a:hover {
  color: var(--main-black);
}
</style>
