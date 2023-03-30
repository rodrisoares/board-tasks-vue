<template>
  <header class="header">
    <h2 class="logo" @click="$router.push('/home')">
      <span class="text-orange">Vue</span><span class="font-weight-light">Tasks</span>
    </h2>

    <nav>
      <router-link tag="a" to="/home">
        <i class="fas fa-home"></i>
        Home
      </router-link>

      <router-link tag="a" to="/">
        <i class="fas fa-clipboard-list"></i>
        Board
      </router-link>
    </nav>
  </header>
</template>

<script>
export default {};
</script>
<style></style>
