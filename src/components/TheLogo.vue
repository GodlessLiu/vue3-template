<template>
  <svg width="500px">
    <symbol id="text">
      <text text-anchor="middle" dominant-baseline="middle" x="50%" y="50%">
        LAF&nbsp;&nbsp;LEARN&nbsp;&nbsp;VUE
      </text>
    </symbol>
    <use href="#text" class="text" />
    <use href="#text" class="text" />
    <use href="#text" class="text" />
    <use href="#text" class="text" />
    <use href="#text" class="text" />
  </svg>
</template>

<script setup lang="ts"></script>

<style lang="css" scoped>
@keyframes stroke {
  to {
    stroke-dashoffset: -400;
  }
}
svg {
  font-size: 8em;
  width: 100vw;
}
.text {
  fill: none;
  stroke-width: 5;
  stroke-dasharray: 70 330;
  stroke-dashoffset: 0;
  animation: stroke 6s infinite linear;
}
.text:nth-of-type(1) {
  stroke: #b80c09;
  animation-delay: -1.2s;
}
.text:nth-of-type(2) {
  stroke: #fffc31;
  animation-delay: -2.4s;
}
.text:nth-of-type(3) {
  stroke: #797e7c;
  animation-delay: -3.6s;
}
.text:nth-of-type(4) {
  stroke: #03f7eb;
  animation-delay: -4.8s;
}
.text:nth-of-type(5) {
  stroke: #b91372;
  animation-delay: -6s;
}
</style>
