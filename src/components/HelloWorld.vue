<template>
  <div class="out-wrap">
      <div class="inner-wrap">
          hhh
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
    .out-wrap {
        background-color: #ff5a33;
          .inner-wrap {
            color: #00ff99;
          }
    }
</style>
