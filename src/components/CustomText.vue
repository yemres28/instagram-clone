<template>
  <component :is="tag" :class="size">
    <slot></slot>
  </component>
</template>

<script>
export default {
  name: "CustomText",
  props: {
    size: {
      type: String,
      default: "normal",
      validator: function (value) {
        return ["normal", "small", "xsmall", " xxsmall"].indexOf(value) !== -1;
      },
    },
    tag: {
      type: String,
      default: "span",
    },
  },
};
</script>
<style scoped>
.small {
  font-size: 12px;
}
.xsmall {
  font-size: 11px;
}
.xxsmall {
  font-size: 10px;
}
</style>
