<template lang="pug">
  .app
    .content
      .content__link [匿名聊天]
      .content__link [暱稱聊天]

</template>

<script>

import './assets/style/normalize.css'
import './assets/style/reset.css'

export default {
  name: 'App',
  components: {
  },
  data () {
    return {
    }
  },
  created () {

  },
  mounted () {
  },
  computed: {

  },
  methods: {
  }
}
</script>

<style lang="stylus">
body
  background: #1E1E1E;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
</style>

<style lang="stylus" scoped>
  .content
    width: 250px;
    height: 250px;
    background: #252526;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: space-evenly;
    padding: 10% 0;
    font-size: 20px;
    box-shadow: 0px 3px 30px #0000007A;
    cursor: pointer;
    &__link
      color: #D4D4D4;
      &:hover
        color: #D7BA7D;

</style>
