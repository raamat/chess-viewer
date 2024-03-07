<template>
  <div class="flex flex-row pt-6">
    <div class="basis-1/4"></div>
    <div class="basis-2/4">
      <Chessboard />
      <div class="block-fen-pgn mt-6">
        <div class="flex">
        <label class="font-medium w-12">FEN</label>
        <input type="text" class="border-inherit border-2 w-full">
      </div>
      <div class="flex mt-6 items-center">
        <label class="font-medium w-12">PGN</label>
        <textarea class="border-inherit border-2 w-full"></textarea>
      </div>
      </div>
      
    </div>
    <div class="basis-1/4"></div>
  </div>
</template>

<script setup lang="ts">
import { Chessboard } from "cw-chessboard";
</script>
