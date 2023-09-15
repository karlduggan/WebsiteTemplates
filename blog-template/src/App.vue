

<template>
  <div>
    <HeaderNavComponent/>
    <RouterView />
  </div>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import HeaderNavComponent from './components/HeaderNavComponent.vue';
export default {
  components: {
  HeaderNavComponent
  }
}
</script>

<style scoped>


</style>
