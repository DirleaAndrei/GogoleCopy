<template>
  <div id="app" class="container-flex">
    <pageToolbar/>
    <pageContent/>
    <pageFooter/>
  </div>
</template>

<script>
import pageContent from './components/page-content'
import pageFooter from  './components/page-footer'
import pageToolbar from './components/page-toolbar'
// import hw from "./components/HelloWorld.vue"

export default {
  name: 'App',
  components: {
    pageToolbar,
    pageFooter,
    pageContent,
    // hw:msg:"dfdsfdsg"
  }

}
</script>

<style>

</style>
