<!DOCTYPE html>
<html>
    <head>
        <title>Calculadora de Estaciones</title>
        <script>
            /*se solicito hacer una calculadora donde al ingresar un numero de 1 a1 12 se mostrara la estacion a la cual pertenece el mes*/


            var mes = prompt("Ingrese el numero de un mes: ")

            

            if(mes >=1 && mes <=12)
                {
                    if(mes == 1 || mes == 2 || mes == 12)
                        {
                         alert("Es invierno")}

                    if(mes == 3 || mes == 4 || mes == 5)
                        {
                    alert("Es Primavera")
                    }
                    if(mes == 6 || mes == 7 || mes == 8)
                        {
                    alert("Es Verano")
                    }
                    if(mes == 9 || mes == 10 || mes == 11)
                        {
                    alert("Es Otoño")
                    }
                    }else{
                        alert("Valor invalido")
                    }
                    alert("Pablo Anibal Juarez Marin, Numero de Carne: 23002242")

        </script>
    </head>
    <body>
        <h1>Calculadora de Estaciones</h1>

        <p>
        se creo una varaible "var" llamada mes la cual con la funcion prompt mostaria una ventana para ingresar el numero requerido.

        Al principio no podria por mis propios meritos encontrar la menera de crear la funcion para que funcionara el programa. 
        Consulte con un compañero para que me pudiera explicar la logica del if y else ya que crei que el if tan solo se podia utilizar una sola vez.
        Entonces me explico que se podria usar mas de una vez y unicamnete cunado no se cumpliera alguna de las condiciones del if. 

        Investigue hacerca de como concatenar y asi poder unir con OR y condicionar la funcion.
        Al principio no funcionaba ya que no habia colocado de forma corecta el else y no me mostraba la alerta, despues no habia colocado un == en 
        un mes. pero despues de intentar, leer y al fin entender el programe al fin funciono.
        
        </p>
    </body>
</html>