<template>
  <div style="padding: 10px">
    <el-row :gutter="20">
      <el-col :span="12">
        <el-card>
          <div style="padding: 10px 0; font-size: 18px">王廷宪</div>
          <el-image style="width: 240px" :src="wx" :preview-src-list="[wx]"></el-image>
          <el-image style="width: 240px; margin-left: 100px" :src="alipay" :preview-src-list="[alipay]"></el-image>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: "Donate",
  data() {
    return {
      wx: "https://pica.zhimg.com/80/v2-40d70c1000e302404df8723ec13bceac_720w.jpg?source=1940ef5c",
      alipay: 'https://pic2.zhimg.com/80/v2-d43ac1ce134ee24fa0d89e55bd30ad7b_720w.jpg?source=1940ef5c'
    }
  }
}
</script>

<style scoped>

</style>
