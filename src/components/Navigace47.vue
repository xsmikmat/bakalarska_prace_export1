<template>
  <router-link to="/okoli-2">
    <div class="button-101"><div class="okol-23 text">Okolí</div></div></router-link
  >
</template>

<script>
export default {
  name: "Navigace47",
};
</script>

<style lang="sass">
@import '../../variables'

.button-101,
.button-102
  align-items: flex-start
  cursor: pointer
  display: flex
  height: 44px
  min-width: 34px
  padding: 13px 0

.okol-23,
.okol-24
  color: $gray
  font-weight: 400
  line-height: 15px
  white-space: nowrap
</style>
