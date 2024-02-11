<!-- <template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style> -->

<template>
    <div id="app">
      <h1>Login Form</h1>
      <p>Welcome back! Please enter your details</p>
      <form action="">
        <label for="">Email: </label><br>
        <input type="email" placeholder="Enter your email " required><br><br>
        <label for="">Password: </label><br>
        <input type="email" placeholder="Enter your password " required><br><br>
        <a href="#">Forget password ? </a><br><br>
        <button type="submit">Login</button><br><br>
        <span class="signup">Don't have an account ? <a href="#">Sign up for free </a></span>
      </form>
    </div>
</template>

<style scoped>
  #app{
    width: 40%;
    margin:150px auto;
    border: 1px solid rgb(255, 255, 255);
    box-shadow: 0px 0px 10px 2px #302e2e;
    border-radius: 50px;
    background: #fff;
    color: #000;
    padding: 20px;
    
  }
  h1,p{
    text-align: center;
  }
  form{
    margin-left: 100px;
    font-size:19px;
  }
  input{
    margin-top: 5px;
    padding: 5px;
    border-radius: 15px;
    border:1px solid rgb(59, 59, 241);
    width: 70% ;
  }
  a{
    text-decoration: none;
  }
  a:hover{
    text-decoration: underline;
  }
  button{
    width: 70%;
    padding: 7px;
    border-radius: 15px;
    background-color: rgb(80, 80, 244);
    border: none;
    font-size:20px;
    color: #fff;
  }
  button:hover{
    background-color: rgb(20, 20, 242);
  }
  #app,.signup{
    padding-bottom: 50px;
  }
</style>
