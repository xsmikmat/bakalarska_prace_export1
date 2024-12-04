<template>
  <router-link to="/kontakt-2">
    <div class="button-70">
      <div class="kontakt-18 text">{{ kontakt }}</div>
    </div></router-link
  >
</template>

<script>
export default {
  name: "Navigace30",
  props: ["kontakt"],
};
</script>

<style lang="sass">
@import '../../variables'

.button-70
  align-items: flex-start
  cursor: pointer
  display: flex
  height: 44px
  min-width: 58px
  padding: 13px 0

.kontakt-18
  color: $gray
  font-weight: 400
  line-height: 15px
  white-space: nowrap
</style>
