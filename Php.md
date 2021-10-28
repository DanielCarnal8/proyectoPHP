# Parte PHP
```php
<?php

$Dia = $_POST["dia"];
$Mes = $_POST["mes"];
$Dias = $_POST["dias"];

$errorlogs= fopen("C:\\xampp\\apache\\logs\\error.log" , "r");
$encontrar = "[$Dia $Mes $Dias";

while (!feof($errorlogs))
{
    $lineas = fgets($errorlogs);
    $cadena = strpos($lineas,$encontrar);
    
        if($cadena !== false)
            {
        echo "$lineas <br>";
            } 
}

fclose($errorlogs);

?>
```
