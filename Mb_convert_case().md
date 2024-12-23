## Sintaxis

 ``` bash
mb_convert_case(string $str, int $mode, string $encoding = mb_internal_encoding()): string

 ```

## Ejemplo:
 ``` bash
<?php
//Cadena original
$texto1 = "¡hola mundo!";
//Convertir a mayúsculas
echo mb_convert_case($texto1, MB_CASE_UPPER); 
echo "<br>";
echo "<br>";
//Convertir a minúsculas
$texto2 = "¡HELLO WORLD!";
echo mb_convert_case($texto2, MB_CASE_LOWER);
echo "<br>";
echo "<br>";
//Convertir al formato de título
echo mb_convert_case($texto2, MB_CASE_TITLE); 
?>

 ```
