<template>
<div id="tab-bar">
  <slot></slot>
</div>
</template>

<script>
export default {
name: "TabBar"
}
</script>

<style scoped>
#tab-bar {
  display: flex;
  position: fixed;
  height: 49px;
  background-color: #eee;
  left: 0;
  right: 0;
  bottom: 0;
  justify-content: center;
  align-items: center;
  box-shadow: 0 -1px 1px rgba(0, 0, 0, .1);
}
</style>
