<template>
  <div>
    <Header></Header>
    <div class="container">
      <router-view></router-view>
     </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
export default {
  name: 'app',
  components: {
    Header
  }
}
</script>

