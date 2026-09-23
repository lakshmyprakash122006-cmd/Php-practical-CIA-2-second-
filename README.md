# Php-practical-CIA-2-second-
Program 
<html>
<body>

<h2>College Student Login</h2>

<form method="post">

Username:
<input type="text" name="username"><br><br>

Password:
<input type="password" name="password"><br><br>

<input type="submit" name="login" value="Login">

</form>

<?php

if(isset($_POST['login']))
{
    $username = $_POST['username'];
    $password = $_POST['password'];

    if($username == "student" && $password == "1234")
    {
        echo "Login Successful";
    }
    else
    {
        echo "Invalid Username or Password";
    }
}

?>

</body>
</html>

output:
Login Successful

