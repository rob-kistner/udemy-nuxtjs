<template>
  <h1>A single user, with ID {{ $route.params.id }}</h1>
</template>

<script>
export default {
  // checks to see if the user ID was a number or not
  validate(data) {
    return /^\d+$/.test(data.params.id)
  }
}
</script>

<style>

</style>
