<template>
  <div style="height:100%;">
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>
</template>

<script type="es6">

  export default {
    components: {},
    data() {
      return {}
    },
    methods: {
      //设置底栏高亮项
      active() {
        return '/' + this.$route.path.split("/")[1];
      },
    },
    mounted() {

    }
  }
</script>
<style>

</style>
