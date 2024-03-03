<template>
   <div class="container">
    <div class="main"><Chessboard /></div>
    <div class="sidebar">
      <button class="btn">Жми</button>
    </div>
    
   </div>
</template>

<script setup lang="ts">
import { Chessboard } from "cw-chessboard";
</script>

<style scoped>
  .main {
    width: 500px;
    height: 500px;
    background-color: black;
  }


</style>
