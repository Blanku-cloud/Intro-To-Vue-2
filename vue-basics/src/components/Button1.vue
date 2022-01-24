<template>
  <button><slot></slot></button>
</template>

<script>
export default {
  name: "Button",
};
</script>

<style scoped>
button {
  background: blue;
}
/* button {
  border: none;
  background-color: transparent;
  font-family: inherit;
  padding: 0;
  cursor: pointer;
}

a,
button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background-color: #1572a1;
  color: #fff;
  border-radius: 8px;
  box-shadow: 0 3px 5px rgba(0, 0, 0, 0.18);
  padding: 0.25em 0.75em;
  min-width: 10ch;
  min-height: 44px;
  text-align: center;
  line-height: 1.1;
} */
</style>
