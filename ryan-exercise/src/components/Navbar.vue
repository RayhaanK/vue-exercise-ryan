<template>
  <div>
    <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <!-- <router-link to="/">Home</router-link> -->
          <a class="nav-link active" aria-current="page" href="/">Home</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
  export default {
  }
</script>

<style scoped>
    .navbar {
      background-color: crimson;
    }

    a {
      font-size: 1.2rem;
    }

    a:hover {
      color: cornflowerblue !important;
    }
</style>