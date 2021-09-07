<template>
  <div>
    <nav class="navbar navbar-expand-sm shadow-sm navbar-light bg-white fixed-top">
      <div class="container">
          <nuxt-link to="/" class="navbar-brand">FireExrent</nuxt-link>
        <button
          class="navbar-toggler d-lg-none"
          type="button"
          data-toggle="collapse"
          data-target="#collapsibleNavId"
          aria-controls="collapsibleNavId"
          aria-expanded="false"
          aria-label="Toggle navigation"
        ></button>
        <div class="collapse navbar-collapse" id="collapsibleNavId">
          <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
            <li class="nav-item">
              <NuxtLink class="nav-link" to="/products">Products</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink class="nav-link" to="/my-items">My Items</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
</style>