<template>
  <router-link to="/o-ubytovani-2">
    <div class="button-25">
      <div class="o-ubytovn-5 text">{{ oUbytovn }}</div>
    </div></router-link
  >
</template>

<script>
export default {
  name: "Navigace11",
  props: ["oUbytovn"],
};
</script>

<style lang="sass">
@import '../../variables'

.button-25
  align-items: flex-start
  cursor: pointer
  display: flex
  height: 44px
  min-width: 80px
  padding: 13px 0

.o-ubytovn-5
  color: $gray
  font-weight: 400
  line-height: 15px
  white-space: nowrap
</style>
