<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2 v-show='showText'>{{ subtitle }}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'HelloWorld.vue file is changed!',
      subtitle: 'This is subtitle!',
      showText: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
