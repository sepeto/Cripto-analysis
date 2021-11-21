<template>
  <!-- @click="buttonClick" -->
  <button
    class="
      bg-transparent
      hover:bg-green-500
      text-green-700
      font-semibold
      hover:text-white
    "
  >
    <slot> </slot>
  </button>
</template>

<script>
export default {
  name: 'PxButton',

  /*methods: {
    buttonClick() {
      this.$emit('custom-click')
    }
  }*/
}
</script>
