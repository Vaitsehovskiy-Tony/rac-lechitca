<template>
  <div class="conteiner-info">
    <p class="info_section"><slot>текст параграфа</slot></p>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.conteiner-info {
  color: #666666;
}

.info_section {
  width: 340px;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 22px;
}
@media (min-width: 1280px) and (max-width: 1439px) {
  .info_section {
    width: 305px;
    font-size: 16px;
    line-height: 20px;
  }
}
</style>
