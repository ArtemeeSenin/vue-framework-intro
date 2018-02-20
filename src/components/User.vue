<template>
  <div id="user">
    <h3>Userpage</h3>
    <p>My username is {{username}}</p>
  </div>
</template>

<script>
export default {
  data(){
    return {
      username: 'Artemee'
    }
  }
}
</script>

<style>
  p {
    color: cornflowerblue;
    font-family: Arial, Helvetica, sans-serif;
  }
</style>
