<template>
    <h1>La mia prima app con Vue CLI!</h1>
</template>

<script>
export default {
  name: 'myFirstTitle',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
h1 {
    font-size: 2.5rem;
    color: greenyellow;
    text-decoration: underscore;
}
</style>
