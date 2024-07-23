<template>
  <header>
    <div class="container">
      <img
        src="https://res.cloudinary.com/lereacteur-apollo/image/upload/v1704448979/RNCP31114/cours-vue/exo-sem-1/my-blog-avatar_xhjc4e.png"
        alt="Avatar du blog"
      />

      <h2>My blog</h2>
    </div>
  </header>
</template>

<style scoped>
header {
  height: var(--header-height);
  border-bottom: 3px solid var(--yellow);
  padding: 10px 0;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

img {
  height: 100%;
}
</style>
