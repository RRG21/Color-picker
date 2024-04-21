<!DOCTYPE html>
<html>
    <head>
        <title> color-picker </title>
    </head>
    <body id="display-color">
        <div class="color-picker">
            <input type="color" namne=" "
            id="color-picker"
            onchange="updatecolor()">
        </div>
        <script>
            let color=document.getElementById
            ("color-picker");
            function updatecolor(){
                document.getElementById
                ("display-color").style.backgroundColor=color.value
            }
        </script>
    </body>
</html>
