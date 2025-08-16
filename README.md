
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>Login</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: linear-gradient(to bottom, #1e2a38, #0f1722);
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

  .login-box {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      border-radius: 10px;
      padding: 40px 30px;
      width: 300px;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
      color: white;
    }

    .login-box h2 {
      text-align: center;
      margin-bottom: 30px;
    }

    .input-group {
      position: relative;
      margin-bottom: 20px;
    }

   .input-group input {
      width: 100%;
      padding: 12px 40px 12px 40px;
      border: none;
      border-radius: 30px;
      outline: none;
      background: #ffffff10;
      color: #fff;
    }

    .input-group i {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      color: #ccc;
    }

    .input-group .icon {
      left: 15px;
    }

    .input-group .toggle-password {
      right: 15px;
      cursor: pointer;
    }

    .login-box button {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 30px;
      background: #3b82f6;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }

    .login-box .register {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
    }

    .login-box .register a {
      color: #3b82f6;
      text-decoration: none;
    }
  
  
  </style>
</head>
<body>
  <div class="login-box">
    <h2>Login</h2>
    <div class="input-group">
      <i class="icon">👤</i>
      <input type="text" placeholder="Username" required="text">
    </div>
    <div class="input-group">
      <i class="icon">🔒</i>
      <input type="password" id="password" placeholder="Password" required="text">
      <i class="toggle-password" onclick="verPassword()">
        👁️</i>
      
      
      
    </div>
    <button>Login</button>
    <div class="register">
      você esqueceu tua password? <a href="#">Register</a>
      
    </div>
  </div>

  <script>
 
  
  
  function verPassword(){
    
    let input=document.querySelector("#password");
    
    let veri=input.type=input.type
       
   if(veri==="password"){
     
     input.type="text";
     
   }else{    
     
     input.type="password";
             
   }   
       
  }
  
  </script>
  

  
  </body>
   </html>
