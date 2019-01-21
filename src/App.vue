<template>
  <div id="app">
    <leftNav></leftNav>
    <left-nav></left-nav>
    <div class="main">

      <router-view/>
    </div>
  </div>
</template>
<script>
import leftNavigation from '@/components/common/leftNav'
export default {
  name: 'App',
  components: {
    leftNav: leftNavigation
  }
}
</script>

<style>
body{margin: 0; height: 100%;}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow: hidden;
  /* margin-top: 60px; */
}
.main{
  float: left;overflow: hidden; width: 95%; height:100%; background: #eff2f7;
}
</style>
