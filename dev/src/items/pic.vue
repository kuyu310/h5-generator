<template>
  <img :src="item.bgImg" v-if="item.bgImg">
</template>

<script>
    export default {
        props:['item'],
    }
</script>
<style lang="scss" scoped>
  img{
      width:100%;
      height: 100%;
      position: absolute;
      top: 0;
      left: 0;
  }
</style>
