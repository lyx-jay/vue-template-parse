<script setup lang="ts">
import Source from '../components/Source.vue';
import EditorVue from '../components/Editor.vue';
</script>

<template>
  <!-- <main class="main">
    <div class="source-wrapper">
      <Source />
    </div>
    <div class="transformed-wrapper">
  
    </div>
  </main> -->
  <EditorVue />
</template>

<style scoped lang="less">
.main {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
  .source-wrapper {
    width: 48%;
    height: 100%;
    background-color: pink;
  }
  .transformed-wrapper {
    width: 48%;
    height: 100%;
    background-color: bisque;
  }
}
</style>