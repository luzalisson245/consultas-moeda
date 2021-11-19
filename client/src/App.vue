<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    <template>
      <div class="container">
        <button type="button" class="btn btn-primary">{{ msg }}</button>
      </div>
    </template>
  }
}
</script>

<style>
#app {
  margin-top: 60px
}
</style>
