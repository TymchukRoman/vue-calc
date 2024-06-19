<script setup lang="ts">
import Calculator from "./components/Calculator.vue";
</script>

<template>
  <div class="root">
    <header>
      <h3>Calculator VUE</h3>
    </header>

    <main>
      <Calculator />
    </main>

    <footer>
      Footer
    </footer>
  </div>
</template>

<style scoped>
body {
  margin: 0px !important;
}

.root {
  width: 100%;
  height: calc(100vh - 16px);
  display: flex;
  flex-direction: column;
}

header,
main,
footer {
  width: 100%;
}

header,
footer {
  height: 40px;
}

main {
  height: calc(100% - 80px);
}

header>h3 {
  margin: 10px 0px;
}
</style>
