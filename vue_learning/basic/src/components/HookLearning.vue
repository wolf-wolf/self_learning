<template>
  <h1>只是为了测试Vue的生命周期函数</h1>
</template>

<script>
  export default {
    name: "HookLearning",
    data: function () {
      return {};
    },
    beforeCreate() {
      console.log(`${new Date().getTime()} in beforeCreate status`);
    },
    created() {
      console.log(`${new Date().getTime()} in created status`);
    },
    beforeMount() {
      console.log(`${new Date().getTime()} in beforeMount status`);
    },
    mounted() {
      console.log(`${new Date().getTime()} in mounted status`);
    },
    beforeUpdate() {
      console.log(`${new Date().getTime()} in beforeUpdate status`);
    },
    updated() {
      console.log(`${new Date().getTime()} in updated status`);
    },
    activated() {
      console.log(`${new Date().getTime()} in activated status`);
    },
    deactivated() {
      console.log(`${new Date().getTime()} in deactivated status`);
    },

    beforeDestroy() {
      console.log(`${new Date().getTime()} in beforeDestroy status`);
    },

    destroyed() {
      console.log(`${new Date().getTime()} in destroyed status`);
    },
    errorCaptured() {
      console.log(`${new Date().getTime()} in errorCaptured status`);
    },

  }
</script>

<style scoped>

</style>
