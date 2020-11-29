<template>
  <div>
<button class="button" :class="{
  'is-primary': primary,
  'is-info' : info,
  'is-link' : link,
  'is-white': white,
  'is-light' : light,
  'is-dark' : dark,
  'is-black': black,
  'is-text' : text,
  'is-ghost' : ghost,
   'is-success': success,
  'is-warning' : warning,
  'is-danger' : danger,
  'is-small': small,
  'is-normal' : normal,
  'is-large' : large,
  'is-outlined': outlined,
  'is-inverted' : inverted,
  'is-hover' : hover,
  'is-focus': focus,
  'is-active' : active,
  'is-loadning' : loading,
   'is-disabled': disabled,
  'is-fullwidth' : fullwidth,
  'is-rounded' : rounded,
  'has-addons' : addons,
}"><slot></slot>
  </div>
</template>

<script>
export default {
  name: "Btn",
  props: {
    primary: Boolean,
    info: Boolean,
    link: Boolean,
    white: Boolean,
    light: Boolean,
    dark: Boolean,
    black: Boolean,
    text: Boolean,
    ghost: Boolean,
    success: Boolean,
    warning: Boolean,
    danger: Boolean,
    small: Boolean,
    normal: Boolean,
    large: Boolean,
    outlined: Boolean,
    inverted: Boolean,
    rounded: Boolean,
    hover: Boolean,
    focus: Boolean,
    active: Boolean,
    loading: Boolean,
    disabled: Boolean,
    fullwidth: Boolean,
    addons: Boolean,
}
}
</script>

<style scoped>

</style>