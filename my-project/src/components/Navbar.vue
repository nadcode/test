<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="https://github.com/avgkenny">avgKenny</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link"><router-link to="/Home">Home</router-link></a>
      </li>
      <li class="nav-item">
        <a class="nav-link"><router-link to="/firstproject">FirstProject</router-link></a>
      </li>
    </ul>
  </div>
</nav>
</template>
<script>
export default {
    name: "Navbar"
}
</script>