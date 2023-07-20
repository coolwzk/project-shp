<template>
  <div>
    <el-container>
      <el-header>
        <Header />
      </el-header>
      <el-main> </el-main>
    </el-container>
  </div>
</template>

<script>
import Header from "@/components/Header/index.vue";

export default {
  name: "app",
  components: {
    Header,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
html,
body {
  width: 100%;
  height: 100%;
}
div {
  width: 100%;
  height: 100%;
}
.el-container {
  width: 100%;
  height: 100%;
  padding: 0;
}
</style>
