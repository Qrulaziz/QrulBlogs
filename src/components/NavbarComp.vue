<template>
  <nav>
    <RouterLink to="/"><h1 class="logo">QrulBlogs</h1></RouterLink>
    <div class="container-nav-menu">
      <ul class="nav-links">
        <RouterLink to="/math">
          <li>MATH</li>
        </RouterLink>
        <RouterLink to="/technology">
          <li>TECHNOLOGY</li>
        </RouterLink>
        <RouterLink to="/gaming">
          <li>GAMING</li>
        </RouterLink>
        <RouterLink to="/food">
          <li>FOOD</li>
        </RouterLink>
      </ul>
      <div class="container-login-signup">
        <RouterLink to="/login">Login</RouterLink>
        <RouterLink to="/signup">Signup</RouterLink>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.container-nav-menu {
  display: flex;
  gap: 40px;
}

.container-login-signup {
  display: flex;
  gap: 20px;
}

.logo {
  font-weight: bold;
}
.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

a {
  text-decoration: none;
}
</style>
