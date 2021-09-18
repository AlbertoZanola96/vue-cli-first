<template>
<div>
  <img src="../assets/vueart.png" alt="">
</div>
</template>

<script>
export default {
  name: 'hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
img {
  border-radius: 30px;
}
</style>