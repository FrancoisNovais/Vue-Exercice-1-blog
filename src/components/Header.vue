<template>
  <header>
    <div class="header container">
      <div>
        <img
          src="https://res.cloudinary.com/lereacteur-apollo/image/upload/v1704448979/RNCP31114/cours-vue/exo-sem-1/my-blog-avatar_xhjc4e.png"
          alt="Avatar du blog"
        />
      </div>
      <div><h1>My blog</h1></div>
    </div>
  </header>
</template>

<style scoped>
header {
  border-bottom: 3px solid var(--main-yellow);
}
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: var(--header-height);
}
.header img {
  width: 60px;
}
h1 {
  font-size: 32px;
  font-weight: bold;
}
</style>
