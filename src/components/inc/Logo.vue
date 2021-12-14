<template>
  <h1 class="logo">
    <router-link to="/">
      <i class="fa fa-book" />
      &nbsp;리선생`s Vue 도서관리
      <small>v 0.10</small>
    </router-link>
  </h1>
</template>

<script>
export default {
  name: "Logo",
};
</script>

<style lang="scss" scoped>
h1.logo {
  font-size: 1em;
  margin-bottom: 0;
  @include flex;
  a {
    @include flex($v: center);
    padding: 0.75em;
  }
}
</style>
