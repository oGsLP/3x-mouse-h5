<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link :to="{name:'Color'}">Color</router-link> |
      <router-link :to="{name:'Interact'}">Interact</router-link> |
      <router-link :to="{name:'Scan'}">Scan</router-link> |
      <router-link :to="{name:'Wash'}">Wash</router-link> |
      <router-link :to="{name:'Share'}">Share</router-link> |
    </div>
    <router-view/>
  </div>
</template>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px

</style>
