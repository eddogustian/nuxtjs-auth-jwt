<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <div class="container">
        <nuxt-link class="navbar-brand" to="/">Jwt CRUD</nuxt-link>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <nuxt-link class="nav-link" to="/dashboard">Dashboard</nuxt-link>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <nuxt-link class="nav-link" to="/Login">Login</nuxt-link>
            <nuxt-link class="nav-link" to="/register">Register</nuxt-link>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>