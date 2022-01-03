<template>
  <div id="one">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'one',
  data () {
    return {
      msg: 'I am one'
    }
  }
}
</script>

<style>
body {
  margin: 0px;
  background: red;
}

#one {
  height: 20vh;
}
</style>
