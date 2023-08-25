<template>
  <div id="App">
    <div class="container">
      <div class="login-page">
        <div class="rhym-logo">
        <img src="../src/assets/AAQ-1904.png" class="logo" />
      </div>
      <div class="input-container">
        <div class="icon-container">
          <img src="../src/assets/reset-password.svg"  class="icon"/>

        </div>
      </div>
      </div>
    </div>
    </div>

</template>
<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
 
  data() {
    return {
     
    }
  },
  methods: {
    
  }
} 
</script>


<style>
#App {
  width: 100%;
  height: 100vh;
 
}
.container {
  display: flex;
  justify-content: center;

}
.rhym-logo{
  background-image: url('../src/assets/Path 34333.svg');
  height: 15vh;
  width: 100%;
  background-size: cover;
  text-align: center;
  
}
.login-page {
  width:50vw;
  height: 100vh;
  background-image:url('../src/assets/Artboard 1@2x.png') ;
  background-color: rgb(19, 4, 71);
  background-size: cover;
 }
.logo {
  width: 20vw;
  height:9vh;
  margin:20px;
}

</style>