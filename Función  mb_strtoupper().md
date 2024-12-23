
## Sintaxis
``` bash
mb_strtoupper(string $str, string $encoding = mb_internal_encoding()): string
```

## Ejemplo:
``` bash
<?php
// Cadena original
$texto = "Tyranitar vs Salamance";
// Convertir a mayúsculas con soporte para caracteres especiales
$resultado = mb_strtoupper($texto);
echo $resultado;
?>
```
