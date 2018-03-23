<template>
  <div id="app">
    <div class="mag" @click="handleClick">{{massage}}</div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      massage: 'hello world'
    }
  },
  methods: {
    handleClick () {
      this.massage = 'bey world'
    }
  }

}
</script>

<style scoped>
  .mag {
    color: red;
  }
</style>
