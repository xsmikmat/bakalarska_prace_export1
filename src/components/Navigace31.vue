<template>
  <router-link to="/o-ubytovani-3">
    <div class="button-75">
      <div class="o-ubytovn-17 text">{{ oUbytovn }}</div>
    </div></router-link
  >
</template>

<script>
export default {
  name: "Navigace31",
  props: ["oUbytovn"],
};
</script>

<style lang="sass">
@import '../../variables'

.button-75
  align-items: flex-start
  cursor: pointer
  display: flex
  height: 44px
  min-width: 101px
  padding: 13px 0

.o-ubytovn-17
  color: $gray
  font-weight: 400
  line-height: 15px
  width: 101px
</style>
