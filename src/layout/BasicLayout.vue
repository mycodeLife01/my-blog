<template>
  <div class="basicLayout">
    <el-container>
      <el-header class="header">
        <GlobalHeader/>
      </el-header>
      <el-main class="main">
        <router-view></router-view>
      </el-main>
      <el-footer class="footer">Footer</el-footer>
    </el-container>
  </div>
</template>

<script setup lang="ts">
import GlobalHeader from '@/components/GlobalHeader.vue'
</script>

<style scoped>
  #app .header {
    margin-bottom: 60px;
  }
</style>
