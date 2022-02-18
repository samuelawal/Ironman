<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <div class="navbar-brand">
        <a href="/" aria-current="page">
          <img src="../assets/images/logo.png" />
        </a>
      </div>
      <div class="navbar-collapse collapse">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item px-4">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item px-4">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item px-4">
          <a class="nav-link" href="#">Video</a>
        </li>
        <li class="nav-item px-4">
          <a class="nav-link" href="#">Gallery</a>
        </li>
        <li class="nav-item px-4">
          <a class="nav-link" href="#">Contact</a>
        </li>
        <li class="nav-item px-4 pt-2">
        <i class="fa-brands fa-facebook-f px-2"></i>
        <i class="fa-brands fa-instagram px-2"></i>
        <i class="fa-brands fa-twitter px-2"></i>
        </li>
      </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");
a {
  color: #ffffff;
}
ul,
li {
  font-size: 17px;
  color: #ffffff;
  font-family: "Montserrat", sans-serif;
}
</style>
