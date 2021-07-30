<template>
  <div id="app">
    <Auth v-if="!username" @getUsername="saveUsername($event)"></Auth>
    <Chat v-else></Chat>
  </div>
</template>

<script>

import Chat from "@/components/Chat";
import Auth from "@/components/Auth";
export default {
  name: 'App',
  components: {
    Auth,
    Chat
  },
  data: function () {
    return {
      username: ''
    }
  },
  methods: {
    saveUsername(username) {
      console.log(username)
      this.username = username
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
