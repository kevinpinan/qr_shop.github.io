<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="ID=edge">
        <meta name="viewport" content="width-device-width, initial-scale=1.0">
        <title>Login</title>

        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Nanum+Brush+Script&display=swap" rel="stylesheet">

    </head>


    <style>

        :root{
            --Principal: #8F2727;
            
        }
        
        body{
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        .login{
           
            width: 100;
            height: 100vh;
            display: grid;
            place-items: center;
        }

        .form-container{
            display: grid;
            
            width: 400px;
        }

        .login_imagen{
            
            
            justify-self: center;
        }
        .QRSHOP{
            font-family: 'Nanum Brush Script', cursive;
            font-style: normal;
            font-size: 47.5px;
            position: relative;
            top: -80px;
            justify-self: center;
            margin-bottom: -10px;
            
            

        }

        .logo_proyecto{
            top: -50px;
            position: relative;
            justify-self: center;
        }
        .form{
            display: flex;
            flex-direction: column;
            margin-bottom: 25px;
            justify-self: center;
        }

        .input{
            
            border: none;
            border-radius: 50px;
            height: 60px;
            padding: 80px;
            margin-bottom: 25px;
        }

        .form2{
            display: -moz-deck;
            flex-direction: column;
            margin-bottom: 25px;
            justify-self: center;
            border: 20px #8F2727;
        }
       




        




    </style>


    <body>
        <div class="login">
            <div class="form-container ">

                <img class="login_imagen" src="DISE??O EN HTML/IMAGENES/login_imagen.png" alt="">
                <img class="logo_proyecto" src="DISE??O EN HTML/IMAGENES/logo_proyecto.png" alt="">
                <h3 class="QRSHOP">QR SHOP </h3>

                <form action="/" class="form">
                    
                    <input type="Usuario" id="idusuario" placeholder="Usuario"> 
                    
                   
                    
                </form>

                <form action="/" class="form2">
                    
                    
                    <input type="Contrase??a" id="idcontrase??a" placeholder="Contrase??a"> 
                    
                </form>

                <h3 class="Olvid_contra">??Olvidaste tu contrase??a? </h3>
                <h3 class="Iniciar_sesion">Iniciar sesi??n con</h3>

                <input type="submit" value="INICIAR SESI??N" class="boton_login">

                <img class="logo_apple" src="DISE??O EN HTML/IMAGENES/apple_logo.png" alt="">
                <img class="logo_google" src="DISE??O EN HTML/IMAGENES/google_logo.png" alt="">
                <img class="logo_facebook" src="DISE??O EN HTML/IMAGENES/facebook_logo.png" alt="">

                <h3 class="No_cuenta" >No tienes cuenta"</h3>
                <h3 class="registrate">Registrate</h3>

                

                

            </div>
             
            

        </div>
        
        
        
       

       



    </body>


</html>
