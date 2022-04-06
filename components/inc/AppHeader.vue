<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="/images/panda.jfif" class="logo-img" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <nuxt-link class="nav-link active" aria-current="page" to="/"
                >Home</nuxt-link
              >
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/about">About Us</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/services">Services</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/contact">Contact Us</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/guest">GetAllUsers</nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
.logo-img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
}
</style>
