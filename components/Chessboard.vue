
<template>
  <div class="board-wrap">
    <TheChessboard :fen="fen" :width="100" :height="100" />
  </div>
</template>


<script setup>
import { TheChessboard } from 'vue3-chessboard';
import 'vue3-chessboard/style.css';
defineProps({
  fen: {
    type: String,
    default: 'start'
  }
})
</script>

<!-- <style>
.board-wrap {
  height: 100vh;
  /* width: 1vw; */
  width: 40%;
   max-width: 300px; 
   max-height: 300px;
  /* height: 1vh; */
  aspect-ratio: 1/1;
}
</style> -->


<style>
.board-wrap{
  width: 240px;
  aspect-ratio: 1/1;
  display: inline-block;
  vertical-align: top;   /* no baseline drop */
  line-height: 0;        /* remove line-box space */
}
</style>