<script>
export default {
  props: {
    name: {
      type: String,
      required: true
    }
  },
  computed: {
    iconPath() {
      return require(`../assets/icons/${this.name}.svg`)
    }
  }
}
</script>

<template>
  <img :alt='`${name} icon`' :class='$style.small' :src='iconPath' />
</template>

<style lang='scss' module>
.small {
  width: 30px;
  display: inline-block;
}
</style>
