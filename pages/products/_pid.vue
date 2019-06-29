<template>
  <div>
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/products">Back to products</nuxt-link>
    <h1>Viewing product {{ $route.params.pid }}</h1>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
