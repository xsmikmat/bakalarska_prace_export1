<template>
  <router-link to="/fotogalerie-1">
    <div class="button-77">
      <div class="fotogalerie-18 text">{{ fotogalerie }}</div>
    </div></router-link
  >
</template>

<script>
export default {
  name: "Navigace33",
  props: ["fotogalerie"],
};
</script>

<style lang="sass">
@import '../../variables'

.button-77
  align-items: flex-start
  cursor: pointer
  display: flex
  height: 44px
  margin-left: 21px
  min-width: 77px
  padding: 13px 0

.fotogalerie-18
  color: $gray
  font-weight: 400
  line-height: 15px
  white-space: nowrap
</style>
