<template>
    <h1>La mia prima app con Vue CLI!</h1>
</template>

<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
    font-size: 60px;
    text-align: center;
    color: #42b983;
}
</style>