RESPUESTAS

Respuesta Ejercicio 1:

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 1</title>
</head>
<body>
  <script type="text/javascript">alert("hola")</script>
</body>
</html>

Respuesta Ejercicio 2:

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 2</title>
</head>
<body>
  <script type="text/javascript">
    // var = a;
    // alert(a);
    //Da este valor: Uncaught SyntaxError: Unexpected token =
    //Dado que no hay variable donde almacenar a, correctamente seria así:
    var a = "a";
    alert(a);
  </script>
</body>
</html>

Respuesta Ejercicio 3:

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 3</title>
</head>
<body>
  <script type="text/javascript">
  <script>
    var miNumero = 3 + "3";
    console.log(miNumero);
    //Respuesta 33 dado que agrega el valor numerico a un string
  </script>
  </script>
</body>
</html>

Respuesta Ejercicio 4:

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 4</title>
</head>
<body>
  <script type="text/javascript">
  // El error radica en que el la variable tiene un espacio y la palabra reservada "var" tiene mayuscula, correctaente seria algo asi:
    var misVacaciones = "me faltan" + " " + 45 + "días para las vacaciones";
    alert(misVacaciones);
  </script>
</body>

Respuesta Ejercicio 5:

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio 5</title>
</head>
<body>
  <script type="text/javascript">
  var a = parseInt(prompt("ingresa un número"));
  var b = parseInt(prompt("ingresa otro número"));
  var c = (a + b);
  alert('la suma es ' + c );
  </script>
</body>
</html>
