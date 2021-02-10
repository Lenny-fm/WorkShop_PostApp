<template>
    <div>
        <!-- HEADER -->
        <header class="header">
                <h1 class="header-logo">PostApp</h1>
                    <h2>Home</h2>
                    <h2>Login</h2>
                    <h2>Sign up !</h2>
        </header>
    <div class="test">
        <div class="container">
            <h1 class="HeaderLogin">User Login</h1>
            <input type="text" placeholder="Username" name="uname" required>
            <input type="password" placeholder="Password" name="psw" required>
            <button type="submit">Login</button>
        </div>
    </div>
    </div>

</template>

<script>
    export default {
    }
</script>

<style lang="scss" scoped>
    .header {
        color:white;
        float: right;
        background-color: #45AAF2;
        width: 100%;
        margin-left: 0;
        margin-right: 0;
        height: 120px;
        margin-top: -10px;
        position: relative;
    }
    h2 {
        font-size:xx-large;
        margin-left: 40px;
        float: right;
        font-family: 'Roboto', sans-serif;
        font-size: 25px;
        margin-top: 2.8rem;
        margin-right: 20px;
        color: white;
    }
    .header-logo {
        position: absolute;
        top: 2.5rem;
        left: 1rem;
        font-family:'Lobster', cursive;
    }
    input {
        padding: 12px 20px;
        margin: 20px 0;
        display: inline-block;
        border:0px;
        box-sizing: border-box;
        width: 100%;
        text-align: center;
    }
    .test {
        height: 27rem;
        width: 100%;
        size: 20%;
        position: relative;
        .container {
            position: absolute;
            background-color: #45AAF2;
            top: 80%;
            left:50%;
            transform: translate(-50%, -50%);
        }
    }
    h1 {
        font-family:'Lobster', cursive;
        color: white;
        text-align: center;
    }
</style>