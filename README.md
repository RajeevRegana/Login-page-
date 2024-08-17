At first I've created a Simple HTML code :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login</title>
    <link rel="stylesheet" href="login.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="wrapper">
        <form action="">
    <h1>Login</h1>
 <div class="inputbox"><input type="text" placeholder="Username" required><i class='bx bx-user'></i></div>
 <div class="inputbox"><input type="text" placeholder="Password" required><i class='bx bxs-lock-alt' ></i></div>
 <div class="remember-forget"><label><input type="checkbox">Remember me</label>
<a href="#">Forget password ?</a>
</div>
<button type="submit" class="btn">Login</button>
<div class="register-link">
    <p>Don't have an account?
        <a href="#">Register</a>
    </p>
</div>
        </form>
    </div>
</body>
</html>
.
.
.
And then I've Designed the above website using CSS:
@import url("https://fonts.googleapis.com/css2?family=poppins:wght@300;400;500;600;700;800;900&display=swap");
*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
    font-family: "poppins",sans-serif;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
background: url('wp5598365.webp') no-repeat;
background-size: cover;
background-position: center;

}
.wrapper{
    width: 420px;
    background: transparent;
    border: 2px solid white;
   backdrop-filter: blur(5px);
   box-shadow: 0 0 10px grey;
    color: white;
    border-radius: 20px;
    padding: 30px 40px;

}
.wrapper h1{
  font-size: 36px;
  text-align: center;
}
.wrapper .inputbox{
    position: relative;
    width: 100%;
    height: 50px;
    margin: 30px 0;

}
.inputbox input{
    width: 100%;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    border: 2px solid ;
    color: grey;
    border-radius: 40px;
    font-size: 16px;
    color: white;
    padding: 20px 45px 20px 20px;
}
.inputbox input::placeholder{
    color: white;
}
.inputbox i{
    position: absolute;
    right: 20px;
    top: 30%;
    transform: translate(-30%);
    font-size: 20px;
}
.wrapper .remember-forget{
    display: flex;
    justify-content: space-between;
    font-size: 14.5px;
    margin: -15px 0 15px;
}
.remember-forget label input{
    accent-color: white;
    margin-right: 3px;
}
.remember-forget a{
    color: white;
    text-decoration: none;
}
.remember-forget a:hover{
    text-decoration: underline;
}
.wrapper .btn{
    width: 100%;
    height: 45px;
    background: white;
    border: none;
    outline: none;
    border-radius: 40px;
    box-shadow: 0 0 10px rgba(0, 0, 0, .1);
    cursor: pointer;
    font-size: 16px;
    color: #333;
    font-weight: 600;
}
.wrapper .btn:hover{
 background-color:rgb(194, 15, 230);
 color: white;
}
.wrapper .register-link {
    font-size: 14.5px;
    text-align: center;
    margin: 20px 0 15px;

}
.register-link p a{
    color: white;
    text-decoration: none;
    font-weight: 600;
}
.register-link p a:hover{
    text-decoration: underline;
}
.
.
.
.
Take your background image as you like or other wise you can use my one :) 
