<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PERDÓN</title>
<style>
    body{
        background-color:white;}


</style>
    <script>
    
        function accionParaCuandoEllaTeDigaQueSi(){
            alert("YO TAMBIEN TE QUIERO BEBESAURIA🦖❤️")
        }
        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newheigth = (Math.random() * height);

            document.getElementById("btnNo").style.position = "absolute";
            document.getElementById("btnNo").style.left = newWidth +"px";
            document.getElementById("btnNo").style.top = newHeight +"px";
        }
    </script>
</head>
<body>
    <br>
    <br>
    <br>
    <center><h1>¿ME PER🍩🍩 JENISITA MI AMOR?</h1></center>
    
    <center>
    <input type="button" onclick ="accionParaCuandoEllaTeDigaQueSi()" id = "btnSi" Value="SI" />
    <input type="button" onmouseover="mueveElBoton()" id = "btnNo" Value="NO" />
    </center>
    
</body>
</html>
