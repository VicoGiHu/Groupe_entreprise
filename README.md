# Groupe_Projet
pour tous les projets
<!DOCTYPE html>
<head>
  <title>Compte client - OMNES Immobilier</title>
  <meta charset="utf-8">
  <link rel="stylesheet" href="seconnecter_client.css" media="screen" type="text/css" />
</head>

<body>
  <form >
    <h1>Se Connecter</h1>
    <input type="text" placeholder="Email" class="username"><br>
    <br>
    <input type="password" placeholder="Mot de Passe" class="password">
    <br>
    <input type="submit" class="submit" value="LOGIN" ><br>
    <br>  
    <div id="nav">
       <a href="modifier_mdp.html">Mot de passe oublié ?</a><br>
       <br>
       <a href="creation_compte_client.html">Je n'ai pas de compte. Je m'en crée un.</a>
    </div>
  </form>    
 </body>
 <style>
    body {
    background: linear-gradient(45deg, #FC466B, #3F5EFB);
    height: 100vh;
    font-family: arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  form {
    background: rgba(255, 255, 255, .3);
    padding: 3rem;
    height: 320px;
    border-radius: 20px;
    border-left: 1px solid rgba(255, 255, 255, .3);
    border-top: 1px solid rgba(255, 255, 255, .3);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    -moz-backdrop-filter: blur(10px);
    box-shadow: 20px 20px 40px -6px rgba(0, 0, 0, .2);
    text-align: center;
  }
  h1 {
    color: white;
    font-weight: 500;
    opacity: .7;
    font-size: 1.4rem;
    margin-bottom: 60px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, .2);
  }
  
  a{
    font-size:13px ;
    color:black;
  }
  input{
    background: transparent;
    border: none;
    border-left: 1px solid rgba(255, 255, 255, .3);
    border-top: 1px solid rgba(255, 255, 255, .3);
    padding: 1rem;
    width: 200px;
    border-radius: 50px;
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
    -moz-backdrop-filter: blur(5px);
    box-shadow: 4px 4px 60px rgba(0, 0, 0, .2);
    color: white;
    font-weight: 500;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, .2);
    transition: all .3s;
    margin-bottom: 2em;
  }
      
  .submit {
    margin-top: 10px;
    width: 150px;
    font-size: 1rem;
    cursor: pointer;
  }
  
  ::placeholder {
    color: #fff;
  }
  </style>
</html>
