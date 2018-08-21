<template>
  <div class="container">
    <router-view></router-view>
    <app-header></app-header>
  </div>
</template>
<script>
import header from './components/Header';

export default {
  components: {
    appHeader: header,
  },
  data() {
    return {

    }
  }
  
}
</script>
