<template>
  
  <div class="welcome">
    <h1>Welcome to the home of meals!!</h1>
    <router-link to="/meals">Check in here</router-link>

  </div>
</template>

<script>
  export default {
    data() {
      return {
        show: false
      }
    }
  }
</script>
<style>
/* .welcome {
  
} */
  h1 {
    font-size: 5rem;
    background-color: salmon;
    text-align: center;

  }
</style>
