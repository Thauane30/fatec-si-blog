<template>
  <header>
    <nav class="navbar background">
      <div class="navbar-brand ml-5">
        <nuxt-link to="/" class="navbar-item">
          <h2 class="is-size-3 logo is-uppercase">Postador</h2>
        </nuxt-link>

        <a
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div class="navbar-menu">
        <nuxt-link to="/" class="navbar-item is-size-5 mx-3">Início</nuxt-link>
        <nuxt-link to="/CreatePosts" class="navbar-item is-size-5"
          >Criar postagem</nuxt-link
        >
      </div>
    </nav>
  </header>
</template>

<style scoped>
.logo {
  text-decoration: underline;
}

.navbar-item {
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.background {
  background-color: rgb(125, 170, 210);
}
</style>

<script>
export default {
  name: 'Header',
}
</script>
