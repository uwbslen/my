<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Inicio de sesión</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#fafafa;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    width:350px;
    background:white;
    border:1px solid #dbdbdb;
    padding:40px;
    text-align:center;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.logo{
    font-size:36px;
    font-weight:bold;
    margin-bottom:30px;
    color:#262626;
}

input{
    width:100%;
    padding:12px;
    margin:6px 0;
    border:1px solid #ccc;
    border-radius:8px;
    background:#fafafa;
    outline:none;
}

input:focus{
    border-color:#4a90e2;
}

button{
    width:100%;
    padding:12px;
    margin-top:15px;
    border:none;
    border-radius:8px;
    background:#0095f6;
    color:white;
    font-size:16px;
    cursor:pointer;
}

button:hover{
    background:#0077d9;
}

.divider{
    margin:20px 0;
    color:#999;
}

a{
    color:#568518;
    text-decoration:none;
    font-size:14px;
}

.footer{
    margin-top:20px;
    font-size:14px;
}
</style>

</head>
<body>

<div class="container">

<div class="logo">Instagram</div>

<form>
<input type="text" placeholder="Usuario o correo">
<input type="password" placeholder="Contraseña">

<button>Iniciar sesión</button>
</form>

<div class="divider">──────── o ────────</div>

<a href="#">¿Olvidaste tu contraseña?</a>

<div class="footer">
¿No tienes una cuenta?
<a href="#">Regístrate</a>
</div>

</div>

</body>
</html>
