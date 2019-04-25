<template>
  <p class="username">{{username}}</p>
</template>

<script>
export default {
  props: {
    username: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss">
  $size: 50pt;
  $yellow: #DCAE1D;

  .username {
    font-size: $size;
    color: $yellow;

    .icon {
      color: green;
    }
  }
</style>
