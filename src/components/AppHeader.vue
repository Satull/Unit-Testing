<template>
  <div>
    <button v-show="loggedIn">Logout</button>
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  data() {
    return {
      loggedIn: false
    }
  }
}
</script>

<style scoped></style>
