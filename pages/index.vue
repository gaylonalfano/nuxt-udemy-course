<template>
  <div class="container">
    <nuxt-link to="/users">Users</nuxt-link>
    <button @click="$router.push('/products')">Load Products</button>
  </div>
</template>

<script>
export default {};
</script>