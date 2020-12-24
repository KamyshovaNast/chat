<template>
  <div id="app">
      <Container></Container>
      <ChatMessage></ChatMessage>
  </div>
</template>

<script>
import Container from './components/Container.vue'
import ChatMessage from './components/ChatMessage.vue'

export default {
    name: 'App',
    components: {
        Container, ChatMessage
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
  margin-top: 60px;
}
</style>
