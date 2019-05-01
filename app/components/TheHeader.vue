<template>
  <el-menu mode="horizontal" :router="true">
    <el-menu-item index="1" style="pointer-events:none;">
      Nuxt Diary
    </el-menu-item>
    <el-menu-item index="2" :route="{ path: '/posts/'}">
      投稿一覧
    </el-menu-item>
  </el-menu>
</template>
