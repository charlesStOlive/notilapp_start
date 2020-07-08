<template>
  <div id="app">
    <div id="nav" class="bg-primary p-4">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
a {
  @apply text-secondary;
}
</style>
