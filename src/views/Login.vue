<template>
    <div class="login">
        <div class="loginForm">
            <img alt="Vue logo" src="../assets/logo.png"><br/>
            <input type="text" placeholder="Username*" /> <br/>
            <input type="password" placeholder="Password*" /> <br/>
            <button>Login</button>
            <button>Signup</button>
        </div>
    </div>
</template>

<style>
.login{
    text-align:center;
}
.loginForm{
    padding: 15px;
    margin:15px;
    max-width: 400px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 30px;
    box-shadow: 0px 0px 30px gray;
}
.loginForm input{
    font-size:20px;
    padding:5px;
    margin:5px;
    margin-bottom:15px;
    border: none;
    border-bottom: 1px solid gray;
    width:80%;
}
.loginForm h1{
    margin-bottom: 30px;
}
.loginForm button{
    font-size:20px;
    margin:5px;
    padding:5px;
    width:35%;

}
</style>
