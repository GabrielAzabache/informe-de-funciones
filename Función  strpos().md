## Sintaxis

 ``` bash
strpos(string $haystack, string $needle, int $offset = 0): int|false
 ```

## Ejemplo

 ``` bash
<?php
$cadena = "Hola Mundo, bienvenido al mundo PHP";
$posicion = strpos($cadena, "M");
if ($posicion !== false) {
    echo "El caractér esta en la posicion :$posicion"; 
// Salida: El caractér esta en la posicion : 5
} else {
    echo "El caractér no se encontró.";
}
?>

 ```
