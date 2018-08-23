<template>
  <nav class="navbar is-primary" role="navigation">
    <div class="navbar-brand">
    <a class="navbar-item" href="https://japari.press">
      <img src="../public/logo.jpg" alt="FriendsMind">      
    </a>
    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
    </div>
    <div class="navbar-menu is-active">
      <div class="navbar-start">
        <a class="navbar-item">
          Home
        </a>
        <a class="navbar-item">
          Journal
        </a>
        <a class="navbar-item">
          About Us
        </a>
        <a class="navbar-item">
          Join Us
        </a>
      </div>
      <div class="navbar-end">
        <!-- navbar items -->
      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link" href="">
          Language
        </a>
        <div class="navbar-dropdown is-boxed">
          <div class="navbar-item">En</div>
          <hr class="navbar-divider">
          <div class="navbar-item">Zh</div>
          <hr class="navbar-divider">
          <div class="navbar-item">Jp</div>
        </div>
      </div>
        <a class="navbar-item">
          Login
        </a>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
    name: 'fnav',
}
</script>
<style lang="scss">

</style>
