<template lang="pug">
  section.hero.is-success
    .hero-head
      header.nav
        .container
          .nav-left
            .nav-item
              strong 🎧 Platzi Music
          .nav-right.nav-menu
            router-link.nav-item(to="search") Buscar 
            router-link.nav-item(to="about") Nosotros

    .hero-body
      .container.has-text-centered
        h1.title Patzi Music
        h2.subtitle Canciones que estan Vuenisimas!
</template>
