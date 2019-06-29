<template>
  <div>
    <p>This is parent page content…</p>
    <nuxt-link to="/">Home</nuxt-link>
    <input type="text" v-model="userId">
    <button @click="onLoadUser">Load User</button>
    <nuxt-child />
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: ''
    }
  },
  methods: {
    onLoadUser() {
      this.$router.push(`/users/${this.userId}`)
    }
  }
}
</script>

<style>

</style>
