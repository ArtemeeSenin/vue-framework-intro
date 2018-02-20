<template>
  <div id="user">
    <h3>Userpage</h3>
    <p>My username is {{username}}</p>
    <app-info></app-info>
  </div>
</template>

<script>
import Info from './Info.vue';

export default {
  data(){
    return {
      username: 'Artemee'
    }
  },
  components: {
    'app-info': Info
  }
}
</script>

<style>
  p {
    color: cornflowerblue;
    font-family: Arial, Helvetica, sans-serif;
  }
</style>
