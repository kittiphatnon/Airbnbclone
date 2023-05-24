<template>
  <div class="">
    <main-header></main-header>
    <page-content></page-content>
    <main-footer></main-footer>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import PageContent from './components/PageContent.vue'
import MainFooter from './components/MainFooter.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    PageContent,
    MainFooter
  }
}
</script>

<style>
**{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
