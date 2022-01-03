<template>
  <div id="two">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'two',
  data () {
    return {
      msg: 'I am two'
    }
  }
}
</script>

<style>
#two {
  background: gray;
}
</style>
