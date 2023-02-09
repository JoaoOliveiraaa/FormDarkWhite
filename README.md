# FormDarkWhite
Form com funções Dark &amp; White.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Login Dark/Light Mode</title>

</head>
<body>   
    <main id="container">
        <form id="login_form">
          
            <div id="form_header">
                <h1>Login</h1>
                <i id="mode_icon" class="fa-solid fa-moon"></i>
            </div>

           
            <div id="social_media">
              
                <a href="#">
                    <img src="assets/imgs/facebook.png" alt="">
                </a>

                
                <a href="#">
                    <img src="assets/imgs/google.png" alt="Google logo">
                </a>
                
               
                <a href="#">
                    <img src="assets/imgs/github.png" alt="">
                </a>
            </div>

          
            <div id="inputs">
              
                <div class="input-box">
                    <label for="name">
                        Name
                        <div class="input-field">
                            <i class="fa-solid fa-user"></i>
                            <input type="text" id="name" name="name">
                        </div>
                    </label>
                </div>
                
             
                <div class="input-box">
                    <label for="email">
                        E-mail
                        <div class="input-field">
                            <i class="fa-solid fa-envelope"></i>
                            <input type="email" id="email" name="email">
                        </div>
                    </label>
                </div>
                
               
                <div class="input-box">
                    <label for="password">
                        Password
                        <div class="input-field">
                            <i class="fa-solid fa-key"></i>
                            <input type="password" id="password" name="password">
                        </div>
                    </label>
                    
                   
                    <div id="forgot_password">
                        <a href="#">
                            Forgot your password?
                        </a>
                    </div>
                </div>
            </div>

            
            <button type="submit" id="login_button">
                Login
            </button>
        </form>
    </main>

    
    <script type="text/javascript" src="assets/js/script.js"></script>
</body>
</html>
