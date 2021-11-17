<template>
  <div id="app">
    <!-- start nav -->
    <div id="nav">
      <b-navbar toggleable="lg" type="dark" variant="light">
        <b-container class="mt-2 mb-2">
          <img src="../src/assets/img/logo.png" alt="logo.png" />
          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ms-auto">
              <router-link class="ps-3 text-decoration-none" to="/"
                >Home</router-link
              >
              <router-link class="ps-3 text-decoration-none" to="/Service"
                >Service</router-link
              >
              <router-link class="ps-3 text-decoration-none" to="/about"
                >About</router-link
              >
            </b-navbar-nav>
          </b-collapse>
        </b-container>
      </b-navbar>
    </div>

    <router-view />
    <!-- end nav -->
    <!-- start footer -->
    <div class="footer fixed-bottom mt-5">
      <b-container>
        <b-row align-h="between" align-v="center">
          <b-col cols="6">2021 all rights reserved</b-col>
          <b-col cols="4" class="p-2">
          <font-awesome-icon :icon="['fab', 'facebook']" class="icon ms-3"></font-awesome-icon>
          <font-awesome-icon :icon="['fab', 'twitter']" class="icon ms-3"></font-awesome-icon>
          <font-awesome-icon :icon="['fab', 'google']" class="icon ms-3"></font-awesome-icon>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <!-- end footer -->
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nav {
  background-color: var(--white--);
}

#nav a {
  font-weight: bold;
  color: var(--light-gray--);
}

#nav a.router-link-exact-active {
  color: var(--main-color--);
}
#nav img {
  height: 5vh;
}
.footer{
  background-color: var(--main-color--);
  
}
.footer .icon{
  font-size: calc(var(--default-font-size) + 8px);
}
</style>
