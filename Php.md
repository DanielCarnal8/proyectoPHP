# Parte PHP
```php
 <?php

$Dia = $_POST["dias"];
$Mes = $_POST["mes"];
$Año = $_POST["años"];

$errorlogs= fopen("C:\\xampp\\apache\\logs\\error.log" , "r");
$encontrar = "$Mes $Dia";
$encontrar2 = "$Año]";

while (!feof($errorlogs))
{
    $lineas = fgets($errorlogs);
    $cadena = strpos($lineas,$encontrar);
    $cadena2 = strpos($lineas,$encontrar2);
    
        if($cadena !== false)
            {
                if($cadena2 !== false)
                    {
                        echo "$lineas<br>";
                    }
            } 
}

fclose($errorlogs);

?>
```
