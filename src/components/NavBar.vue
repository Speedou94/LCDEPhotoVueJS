<template>
  <nav
    class="navbar is-fixed-top"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="navbar-brand" :class="{ 'is-active': openBurger }">
      <a
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
        @click="openCloseNavbar"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div class="navbar-menu" :class="{ 'is-active': openBurger }">
      <div class="navbar-start">
        <router-link
          to="/"
          class="navbar-item"
          @click="scrollInHome() + openCloseNavbar()"
          >LCDE Photo</router-link
        >

        <router-link to="" class="navbar-item" @click="openCloseNavbar()"
          >Biographie</router-link
        >

        <div class="navbar-item has-dropdown is-hoverable">
          <router-link to="/" class="navbar-link" @click="openCloseNavbar()"
            >Mon materiel</router-link
          >
          <div class="navbar-item has-dropdown is-hoverable">
            <router-link
              to="/Book"
              class="navbar-link"
              @click="openCloseNavbar()"
              >Mon book</router-link
            >
            <div class="navbar-item has-dropdown is-hoverable">
              <router-link to="" class="navbar-link" @click="openCloseNavbar()"
                >Mes services</router-link
              >
            </div>
          </div>
        </div>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <router-link
              to="/Contact"
              class="button is-rounded"
              @click="openCloseNavbar()"
              ><strong>Me contacter</strong></router-link
            >
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      openBurger: false,
    };
  },
  methods: {
    openCloseNavbar() {
      this.openBurger = !this.openBurger;
    },
  },
};
</script>

<style lang="scss" scoped>
a.navbar-item:hover {
  color: #000;
}
.navbar-link:hover {
  color: #000;
}
a.nvabar-item:visited {
  color: white;
}

.navbar-link:not(.is-arrowless)::after {
  border-color: white;
}
</style>
