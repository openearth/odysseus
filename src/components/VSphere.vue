<template>
  <div class="v-sphere">
    <canvas class="sphere"></canvas>
    <video :src="src" autoplay loop controls class="depth" v-if="src"></video>
  </div>
</template>

<script src="components/v-sphere.js"></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="components/v-sphere.scss"></style>
