# aula08-10
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>validar formulario com java script</title>
</head>
<body>
    <h1>Cadastrar Usuarios</h1>
        <form name="formuser" action="enviar.php" method="post">
            Nome: <input type="text" name="Nome" ><br><br>
            E-mail: <input type="text" name="email" ><br><br>
            senha: <input type="password" name="senha" ><br><br>
            <input type="submit" onclick="return validar ()">
        </form>
    </body>
</html>
