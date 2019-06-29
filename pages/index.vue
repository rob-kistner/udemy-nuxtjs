<template>
  <section class="container">
    <nuxt-link to="/users">Users</nuxt-link>
    <nuxt-link to="/products"><button>Go to Products</button></nuxt-link>
  </section>
</template>

<script>
export default {
  components: {
  },
  methods: {
    goToProducts() {
      this.$router.push('/products')
    }
  }
}
</script>

<style>

</style>
