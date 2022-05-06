<script>
export default {
  data() {
    return {
      imagem: [new URL("./img/modelo.jpg", import.meta.url).href],
    };
  },
};
</script>

<template>
  <header id="header" class="header">
    <div class="titulo-header">Quiz</div>
    <div class="logo-header">
      <img :src="imagem[0]" alt="" />
    </div>
  </header>
  <template />
</template>
