<template>
    <div id="app" class="container">
        <span class="spaceLeft" />
        <h1 class="header">{{ msg }}</h1>
        <span class="spaceLeft" />
        <div class="welcome">
            {{welcome}}
        </div>
    </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App!',
      welcome: 'Wonderful!!'
    }
  }
}
</script>

<style lang="css">
  #app {
    color: #56b983;
  }
</style>
