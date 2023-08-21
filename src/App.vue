<template>
  
  <div id="App">
    <img class='img' v-bind:src="img">
    
    <form>
    <div class="card">
      <div class="label-card">
      <input class="label" type="text" placeholder="Enter UserName" required>
      <br/>
      <input class="label" type="password" placeholder="Enter Password" required >
      <br/>
      <button class="button">Sign In</button>
      <p class="name"> {{ name }}</p>
      <h1 class="title">{{ title }}</h1>
      <p class="paragraph">{{ paragraph }}</p>
      <button class="button button1">Reach our Experts</button>
      </div>
      <div class="card-2">
        <div class="text-card">
          <p1 class="card-heading"> {{ title2 }}</p1>
          <p class='para2'>Cyber criminals are leveraging AI to design sophisticated attacks.
            But they need <br> not always use these advanced techniques unless they plan a very targeted attack. <br/>
            Most of the times cyber attacks are launched using simple exploits <br/>
            as basic cyber hygiene is lacking everywhere.</p>
           <div class="img-card">
            <img class='img1' v-bind:src="img1">
            <img class='img1' v-bind:src="img2">
            <img class='img1' v-bind:src="img3">
           </div>
        
            
        </div>
        
      </div>
     </div>
  </form>
 


  </div>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  data() {
    return {
      img3:'https://res.cloudinary.com/do5dyebav/image/upload//b_rgb:632BD3/v1692614058/download_mhhamz.png',
      img2:'https://res.cloudinary.com/do5dyebav/image/upload//b_rgb:6428C4/v1692613830/linkinfd_1_pp6yej.png',
      img1: 'https://res.cloudinary.com/do5dyebav/image/upload//b_rgb:ffffff00,e_improve/v1692613137/twitwer_a3k8vw.png',
      img: 'https://res.cloudinary.com/do5dyebav/image/upload//b_rgb:F0EBEB/v1692590626/logo_qgtngj.png',
      name:'Forgot Password?',
      title:'Dont have an account with us ?',
      paragraph:'Our Yearly Cyber Health Check Plan will help you run your business “securely” at an affordable cost',
      title2:'Health Is Wealth Even In Cyber World…'
    
                  
    }
  },
  methods: {
    
  }
} 
</script>

<style>
#App {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #f0ebeb;
  background-size: cover;
}

.img1 {
  width: 20px;
  margin: 5px;
  padding:8px;
}
.img {
  width: 170px;
  margin: 30px;
  
 
}
.card {
  
  background-size: cover;
  width: 70vw;
  background-color: whitesmoke;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-radius: 25px;
 
  margin-left: 160px;
  padding:10px;
  margin-top: 30px;
  
}
.label-card {
  padding: 50px;
 

}

.label {
  width: 90%;
  font-size: 20px;
  height:4vw;
  border: none;
  border-bottom: 2px solid #815bd3;
  margin: 30px;
  background-color:#f5f5fa ;
}
::placeholder {
  color:rgb(27, 51, 185);
  font-size: 10px;
  font-family:Arial, Helvetica, sans-serif;
 
}


.button{
  background-color: #6428c4;
  color: whitesmoke;
  border-width: 0px;
  
  border-radius: 15px;
  text-align: center;
  margin-top: 15px;
  margin-left: 20px;
  width:10vw;
  height:6vh;
}
.name {
  color:rgb(27, 29, 29);
  font-size:15px;
  font-weight:300px;
  position: relative;
  text-decoration:underline;
  margin-left: 20px;
  margin-top: 18px;
}
.title {
  font-size: 22px;
  font-weight:200px;
  margin-left: 20px;
  margin-top: 100px;

}
.paragraph {
  color:rgb(141, 156, 156);
  font-size: 20px;}

.button1{
  background-color: #e1dde7;
  color: rgb(124, 114, 114);
  border-width: 0px;
  font-size:18px;
  border-radius: 15px;
  text-align: center;
  margin-top: 25px;
  margin-left: 20px;
  width:18vw;
  height:7vh;
  
}
.card-2 {
  
  background-color: #743fc9;
  width: 69vw;
  padding:10px;
  
  height:55vh;
  background-size: cover;
  border-radius: 25px;
  color:#afafb6
 
 
}
.card-heading {
  font-family:Verdana, Geneva, Tahoma, sans-serif;
  font-size:55px;
}
.text-card{
  margin: 20px;
  padding:10px;
}
.para2 {
  font-size:20px;
  font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

</style>
