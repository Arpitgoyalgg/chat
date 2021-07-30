<template>
  <div>
    <h1>
      Please enter a cool or nerdy username
    </h1>
    <input v-model="username">
    <button @click="submit">Submit</button>
    <h1>{{username}}</h1>
  </div>

</template>

<script>
export default {
  name: "Auth",
  data: function () {
    return {
      username: ''
    }
  },
  methods: {
    submit() {
      this.$emit('getUsername',this.username)
    }
  }
}
</script>

<style scoped>

</style>