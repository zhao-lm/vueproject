<template>
  <div class="nav_bar">
    <div class="left"><slot name="left"></slot></div>
    <div class="center"><slot name="center"></slot></div>
    <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<script>
  export default {
    components: {},
    props: {},
    data() {
      return {
      };
    },
    watch: {},
    computed: {},
    methods: {},
    created() {},
    mounted() {}
  };
</script>
<style scoped>
  .nav_bar {
    display: flex;
    height: 44px;
    line-height: 44px;
  }
  .left .right {
    width: 60px;
  }
  .center {
    flex: 1;
    text-align: center;
  }
</style>