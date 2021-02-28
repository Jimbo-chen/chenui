<template>
  <button class="c-btn">提交</button>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.c-btn {
  height: var(--btn-height);
  padding: 0 1em;
  background-color: var(--btn-bg);
  color: var(--font-color);
  border: 1px solid var(--border-color);
  border-radius: var(--border-radius);
  &:hover {
    background-color: var(--btn-hover-bg);
  }
  &:active {
    outline: none;
    background-color: var(--btn-active-bg);
  }
}
</style>