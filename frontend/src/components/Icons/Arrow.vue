<template>
  <svg
    :style="`transform: rotate(${rotate}deg)`"
    fill="currentColor"
    viewBox="0 0 20 20"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
    ></path>
  </svg>
</template>

<script>
export default {
  name: "Arrow",
  props: {
    rotate: {
      type: Number,
      required: false,
      default: 0
    }
  }
};
</script>

<style scoped></style>
