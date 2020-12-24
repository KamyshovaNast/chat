<template>
  <div id="app">
      <Container></Container>
      <ChatWindow></ChatWindow>
  </div>
</template>

<script>
import Container from './components/Container.vue'
import ChatWindow from './components/ChatWindow.vue'

export default {
    name: 'App',
    components: {
        Container, ChatWindow
    },
    data() {
        return {
            username: 'Ivan',
            datatime: '21.12.2019 05:00:50'
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
