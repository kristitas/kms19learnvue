<template>
  <div>
    <btn info>Info</btn>
    <btn dark>Dark</btn>
    <btn rounded>Rounded</btn>
    <btn link>Link</btn><div>
    <btn small>Small</btn>
    <btn normal>Normal</btn>
    <btn large>Large</btn>
    <btn outlined>Outlined</btn>
    <btn inverted>Inverted</btn>
    <btn hovered>Hover</btn>
    <btn focused>Focus</btn>
    <btn active>Active</btn>
    <btn loading>Loading</btn>
    <btn fullwidth>Fullwidth</btn>
    <btn white>White</btn>
    <btn light>Light</btn>
    <btn black>Black</btn>
    <btn text>Text</btn>
    <btn ghost>Ghost</btn>
    <btn success>Success</btn>
    <btn warning>Warning</btn>
    <btn danger>Danger</btn>
  </div>
</template>

<script>
import Btn from "./Btn";
export default {
  name: "ButtonExample",
  components: {Btn}
}
</script>

<style scoped>
</style>