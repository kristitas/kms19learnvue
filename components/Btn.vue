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
  'is-small is-light': small,
  'is-normal' : normal,
  'is-large' : large,
  'is-outlined is-primary': outlined,
  'is-inverted is-danger is-outlined' : inverted,
  'is-hovered is-warning' : hovered,
  'is-focused is-success': focused,
  'is-active' : active,
  'is-loading is-primary' : loading,
  'is-fullwidth is-warning' : fullwidth,
  'is-rounded is-danger' : rounded,
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
    hovered: Boolean,
    focused: Boolean,
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