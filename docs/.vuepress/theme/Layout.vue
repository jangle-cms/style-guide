<template>
  <div class="page">
    <div v-if="$page.frontmatter.home">Home</div>
    <ul>
      <li v-for="item in $page.frontmatter.items">{{item}}</li>
    </ul>
    <Content/>
  </div>
</template>

<style lang="scss">
  .h1 {
    font-family: sans-serif;
  }
</style>
