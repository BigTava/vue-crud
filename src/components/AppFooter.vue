<template>
  <footer>
    <p><slot name="message">Default Footer</slot></p>
    <p><slot name="link"></slot></p>
  </footer>
</template>

<style scoped>
footer {
  text-align: center;
  border-top: 1px solid #88bbd6;
  padding: 10px;
}
</style>
