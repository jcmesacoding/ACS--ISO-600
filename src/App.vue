<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://unapec.edu.do" target="_blank">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRn-FIJ-KUI2zxSv1jUOuc32bSCKdDPIPHvXp-Sau-SZw&s=10" class="logo" alt="Vite logo" />
    </a>
  </div>
  <HelloWorld msg="UNAPEC" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
