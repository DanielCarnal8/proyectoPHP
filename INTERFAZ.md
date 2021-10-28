
# INTERFAZ CON LA QUE BUSCAR LOGS A PARTIR DE LA FECHA

![Captura](https://user-images.githubusercontent.com/72084639/139121877-2ac4d670-c65c-46ce-920a-31509090961c.PNG)

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <title>Logs De Xampp</title>
    
    <style>
        h1.h1{text-align: center; color: white; margin-top: 3%; font-size: 50px;}
        div.semana{text-align: center; color: black; font-size: 22px;}
        div.mes{text-align: center; color: black; font-size: 22px;}
        div.dias{text-align: center; color: black; font-size: 22px;}
        div.pweb{text-align: left; color: black; font-size: 15px; float: right; position: relative; bottom:-430px ;}
        div.boton{text-align: center; color: black;  }
        body {background-color:goldenrod }
        img.andel 
        {
         float: left ;
         position: absolute; width: 175px; height: 63px; top: 0%; right: 0%;
         display: block;
        }
    </style>
</head>

<body>

    <img class="andel" hidden src="andel.png">
    <title>Logs de XAMPP</title>
    <h1 class="h1">Logs de XAMPP</h1>
            
    <form action="proyecto.php" method="post">
        
            <div class="cuadro">
                 
            <div class="semana">
                    <b>Día de la semana</b>     
                        <select name="dia">
                            <option value="Mon"> Mon </option>
                            <option value="Tue"> Tue </option>
                            <option value="Wed"> Wed </option>
                            <option value="Thu"> Thu </option>
                            <option value="Fri"> Fri </option>
                            <option value="Sat"> Sat </option>
                            <option value="Sun"> Sun </option>
                        </select><br>
            </div>
                
            <div class="mes">
                    <b>Mes del año</b>            
                        <select name="mes">
                            <option value="enero"> Jan </option>
                            <option value="febrero"> Fre </option>
                            <option value="marzo"> Mar </option>
                            <option value="abril"> Apr </option>
                            <option value="mayo"> May </option>
                            <option value="junio"> Jun </option>
                            <option value="julio"> Jul </option>
                            <option value="agosto"> Ago </option>
                            <option value="sep"> Sep </option>
                            <option value="Oct"> Oct </option>
                            <option value="nov"> Nov </option>
                            <option value="dic"> Dic </option>
                        </select><br>
            </div>

            <div class="dias">
                    <b>Día del año</b>
                        <select name="dias">
                            <option value="01"> 1 </option>
                            <option value="02"> 2 </option>
                            <option value="03"> 3 </option>
                            <option value="04"> 4 </option>
                            <option value="05"> 5 </option>
                            <option value="06"> 6 </option>
                            <option value="07"> 7 </option>
                            <option value="08"> 8 </option>
                            <option value="09"> 9 </option>
                            <option value="10"> 10 </option>
                            <option value="11"> 11 </option>
                            <option value="12"> 12 </option>
                            <option value="13"> 13 </option>
                            <option value="14"> 14 </option>
                            <option value="15"> 15 </option>
                            <option value="16"> 16 </option>
                            <option value="17"> 17 </option>
                            <option value="18"> 18 </option>
                            <option value="19"> 19 </option>
                            <option value="21"> 21 </option>
                            <option value="22"> 22 </option>
                            <option value="23"> 23 </option>
                            <option value="24"> 24 </option>
                            <option value="25"> 25 </option>
                            <option value="26"> 26 </option>
                            <option value="27"> 27 </option>
                            <option value="28"> 28 </option>
                            <option value="29"> 29 </option>
                            <option value="30"> 30 </option>
                            <option value="31"> 31 </option>
                        </select><br>     
            </div>
            
            <div class="boton">
                    <input type="submit" value="BUSCAR">
            </div>
    </form>

    <div class="pweb"> 
        <p>Página del desarrollador
            <br>
            <a href="https://adoring-bhabha-cb3f8f.netlify.app/"><b>DANIEL</b></a>
            
            </p>
    </div>

</body>

</html>
```
