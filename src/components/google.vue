<template>
  <div>
    <span id="name"></span> <input type="button" id="loginBtn" value="Checking..." onclick="
   if(this.value==='Login') {
    gauth.signIn().then(function(){console.log('gauth.signIn');checkLoginStatus();});

  } else {
    gauth.signOut().then(function(){console.log('gauth.signOut');checkLoginStatus();});

    }"
  >
  </div>
</template>

<script>
    export default {
        name: "google",


      methods: {

      },
      created(){

      }


    }
</script>

<style scoped>

</style>
