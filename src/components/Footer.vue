<template>
  <footer>
    <Logo />
    <a
      href="https://github.com/Seungheon91"
      target="_blank">(c){{ new Date().getFullYear() }} seungheon</a>
  </footer>
</template>
<script>
import Logo from "~/components/Logo";
export default {
  components: {
    Logo,
  },
};
</script>

<style lang="scss" scoped>
footer {
  padding: 70px;
  text-align: center;
  opacity: 0.3;
  .logo {
    display: block;
    margin-bottom: 4px;
  }
}
</style>
