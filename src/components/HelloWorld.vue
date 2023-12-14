<template>
  <div class="hello">
    <div class="value">{{value}}</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    value: {
      type: String,
      default: 'Empty'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.value {
  background-color: #ccc;
}
</style>
