<template>
  <div id="wrapper">
    <nav class="navbar is-dark">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item"><strong>Djackets</strong></router-link>

        <a href="" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbar-menu"></a>
      </div>
    </nav>

    <router-view/>
  </div>
</template>

<style lang="scss">
@import '../node_modules/bulma/';
</style>
