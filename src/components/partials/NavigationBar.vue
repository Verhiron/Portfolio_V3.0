<template>
  <nav class="navbar">
    <div>
      <a class="navbar-brand p-1" href="#">
        <img class="logo-img" src="/src/assets/images/Logo.png">
      </a>
    </div>
    <div>
      <a class="navbar-brand p-1" href="https://github.com/Verhiron" target="_blank">
        <i class="fab fa-github fa-2x"></i>
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavigationBar",
}
</script>

<style scoped>

.logo-img{
  max-width: 120px;
  padding:5px;
  filter: brightness(0) invert(1);
}

.fa-github{
  color: #fff;
}

.fa-github:hover{
  color: #682860;
}

</style>