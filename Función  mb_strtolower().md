## Sintaxis:

 ``` bash
mb_strtolower(string $str, string $encoding = mb_internal_encoding()): string
 ```

## Ejemplo:
 ``` bash
<?php
// Cadena original
$texto = "ESTAMOS UTILIZANDO PHP";
// Convertir a minúsculas con soporte para caracteres especiales
$resultado = mb_strtolower($texto);
echo $resultado;
?>

 ```
