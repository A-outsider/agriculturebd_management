<script setup lang="ts">
import panel from './cpns/panel.vue';

defineOptions({
  name: 'AuthLogin'
})
</script>



<template>
  <div class="login">

    <panel></panel>

  </div>
</template>



<style lang="less" scoped>
.login {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  background: url("../../assets/img/login-bg.svg");
}
</style>
