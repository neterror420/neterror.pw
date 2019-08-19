<template>
  <footer class="site-footer">
    Copyright &copy; NetError {{ new Date().getFullYear() }} - All
    Rights Reserved
    <br />
    If you need help please feel free to message us.
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
}
</script>

<style scoped>
footer {
  background: #eee;
  padding: 20px 10px;
  text-align: center;
  transition: 0.5s ease all;
}
</style>
