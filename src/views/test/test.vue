<template>
  <div class="hello">
    <div class="test">
      <span>{{ msg }}</span>
    </div>
    <div class="test">
      <span>{{ msg2 }}</span>
    </div>
    <div class="test">
      <div>{{ msg2 }}</div>
    </div>
    <div class="test">
      <span>
        <a>1</a>
        <a>2</a>
      </span>
    </div>
    <div class="test">
      <a>1</a>
      <span>
        <a>2</a>
      </span>
      <a>3</a>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Test',
    data () {
      return {
        msg: 'asdasdf哈哈哈哈哈哈哈adasdasd',
        msg2: 'sdfsfdgdfgfdgfd'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "@/assets/css/index.sass";

  h1, h2 {
    font-weight: normal;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
</style>
