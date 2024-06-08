<template>
  <div class="home">
    <div><img class="robot" src="../assets/robot-home.png" alt=""></div>
    <div class="get-started">
      <a href="">Get started</a> building your first robot!
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
.home {
  text-align: center;
}
.robot {
  height: 500px;
}
.get-started {
  padding-top: 20px;
  font-size: 32px;
}
</style>
