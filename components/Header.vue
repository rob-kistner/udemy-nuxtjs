<template>
  <header>
    <ul class="nav-items">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
  header {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 60px;
    background-color: #aaa;
  }
  .nav-items {
    display: flex;
    justify-content: space-around;
    align-items: center;
    list-style-type: none;
    padding: 0;
    margin: 0;
    width: 80%;

    & a {
      text-decoration: none;
      color: black;
      
      &:hover, &:active {
        color: white;
      }
    }
  }
</style>
