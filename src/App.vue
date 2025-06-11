<script setup lang="ts">
import zhCN from '@arco-design/web-vue/es/locale/lang/zh-cn'
import Page from './pages/index.vue'
</script>

<template>
  <AConfigProvider
    :locale="zhCN"
  >
    <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
      <!--      <RouterView />-->
      <Page/>
      <!--      <Hello/>-->
    </main>
  </AConfigProvider>
</template>
