# Parte PHP
```php
<?php

$Dia="";
$Mes="";
$Año="";


if(empty($_POST))
{
    echo "Introduce los parametros...";
}else
{
    $errorlogs= fopen("C:\\xampp\\apache\\logs\\error.log" , "r");
    while (!feof($errorlogs))
    {
        
        $Dia = $_POST["dias"];
        $Mes = $_POST["mes"];
        $Año = $_POST["años"];
        $encontrar = "$Mes $Dia";
        $encontrar2 = "$Año]";
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
}

?>
```
