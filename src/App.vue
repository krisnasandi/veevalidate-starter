<template>
  <div id="app">
    <registration-form />
  </div>
</template>

<script>
import RegistrationForm from './components/RegistrationForm'

export default {
  name: 'App',
  components: {
    RegistrationForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
