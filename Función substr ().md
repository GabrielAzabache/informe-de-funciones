## Sintaxis:
``` bash
substr(string $string, int $start, ?int $length = null): string
```

## Ejemplo simple:
``` bash
<?php
$cadena = "Hola Mundo";
echo substr($cadena, 5); // Salida: "Mundo" (empieza en la posición 5 y extrae hasta el final)
?>
```

## Ejemplo con strpos:
``` bash
<?php
$email = "usuario@dominio.com";
$dominio = substr($email, strpos($email, "@") + 1);
echo $dominio; // Salida: "dominio.com"
?>

```
