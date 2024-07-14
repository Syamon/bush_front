<template>
  <HeaderComponent/>
  <router-view/>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
import HeaderComponent from './components/HeaderComponent.vue'

export default defineComponent({
  name: 'App',
  components: {
    HeaderComponent
  }
})
</script>
<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #e1f2f7;
  height: 100vh;
}
</style>
