<template>
  <header class="header">
    <content-container>
      <nav class="nav">
        <div>Menu</div>
        <nuxt-link to="/">Logo</nuxt-link>
        <nuxt-link to="/about">About</nuxt-link>
      </nav>
    </content-container>
  </header>
</template>

<style scoped>
.header {
  background: white;
}

.nav {
  display: flex;
  justify-content: space-between;
  padding-top: 1em;
  padding-bottom: 1em;
}
</style>
