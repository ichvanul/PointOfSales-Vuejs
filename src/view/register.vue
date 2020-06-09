<template>
<div class="signup">
    <form>
    <h2 style="color: #fff;">Register</h2>
    <input type="text" name="username" placeholder="Name"><br><br>
    <input type="text" placeholder="Email"><br><br>
    <input type="password" name="pass" placeholder="Password"><br><br>
    <input type="button" value="Sign Up"><br><br><br><br>
    <div class="account"> Do you have account?<router-link to="/"><a
    style="text-decoration: none; font-family: airbnb; color: #F24F8A;">&nbsp;
    Log In</a></router-link></div>
    </form>
</div>
</template>

<script>
export default {
  name: 'Register',
};
</script>

<style scoped>
@font-face {
  font-family: airbnb;
  src: url('../assets/font/AirbnbCerealBold.ttf')
}

body {
    font-family: airbnb;
    color: #fff;
    background-size: cover;
}

.signup {
    background: #57CAD5;
    border-radius: 10px;
    padding:40px;
    width:320px;
    margin:auto;
    margin-top:80px;
    height:370px;
    margin-left:180px;
    margin:0 auto;
    margin-top:90px;
}

form {
    width: 240px;
    text-align: center;
}

input {
    width: 240px;
    text-align: center;
    background: transparent;
    border: none;
    border-bottom: 1px solid #fff;
    font-family: 'Play', sans-serif;
    font-size: 16px;
    font-weight: 200px;
    padding: 10px 0;
    transition: border 0.5s;
    outline: none;
    color: #fff;
}

input[type=button] {
    border: none;
    width: 190px;
    background: #F24F8A;
    color: white;
    font-size: 16px;
    line-height: 25px;
    padding: 10px 0;
    border-radius: 15px;
    cursor: pointer;
    font-family: airbnb;
}

input[type=button]:hover {
    color: #57CAD5;
    background-color: white;
}

h2 {
    color: #000;
}

::placeholder {
    color:aliceblue;
    opacity: 0.8; /* Firefox */
}

.account {
  font-family: airbnb;
}
</style>
