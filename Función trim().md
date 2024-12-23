## Sintaxis: 
 
 ``` bash
trim(string $string, string $characters = " \n\r\t\v\0"): string
 ```


## Ejemplo:
``` bash
<?php
$texto = "   Hola Mundo   ";
echo trim($texto); // Salida: "Hola Mundo"
$textoConCaracteres = "xxxHola Mundoxxx";
echo trim($textoConCaracteres, "x"); // Salida: "Hola Mundo"
?>

 ```
