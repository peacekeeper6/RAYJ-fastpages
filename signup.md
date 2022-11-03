<head>
    <meta charset="UTF-8">
    <title>Sign-In</title>
</head>
<body style="background-color:#ffffff;">

<br> <h1 style="color: black">Welcome! Sign-up to get started!</h1> <br>

<center>
    <form style="color: black" action="/action_page.php">
        <label for="email">Email Address</label> <br>
        <input type="email" id="email" name="email" required> <br> <br>
        <label for="pass">Password (8 characters minimum):</label> <br>
        <input type="password" id="pass" name="password"minlength="8" required> <br> <br>
        <label for="pass">Repeat Password:</label> <br>
        <input type="password" id="pass" name="password"minlength="8" required> <br> <br> <br>
        <input type="submit" value="Sign-Up"> <br> <br>
    </form>
</center>


</body>
<style>
    h1 {
        text-align: center;
        font-size: 24px;
    }
    body {
        margin: 0;
        padding: 0;
        background: linear-gradient(to bottom right, #E3F0FF, #FAFCFF);
        height: 100vh;
        justify-content: center;
        align-items: center;
    }
    form {
        width: 70%;
        height: 85%;
        background-color: #ffffff;
        border-radius: 20px;
        box-shadow: 0px 25px 40px #1687d933;
    }

</style>
</html>