<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <input oninput="kk()"id="uo">
        
        <h1 id="bri"></h1>
        
        <script>
            function kk(){
                var uo=document.getElementById("uo").value
                var uoo=document.getElementById("bri")
                uoo.innerHTML=uo
            }
        </script>
    </body>
</html>
