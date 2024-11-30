<template>
  <div>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/products">Products</nuxt-link>
      </li>
      <li> <nuxt-link to="/users">Users</nuxt-link></li>
      <li></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
