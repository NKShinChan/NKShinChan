<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hi!!!</title>
</head>

<body style="height: 100%; margin: 0; padding: 0;">
    <div class="bg" style="background: #CCCCCC; display: flex; align-items: center; justify-content: center; height: 100vh; margin: 0; padding: 0;">
        <div class="item" style="text-align: center;">
            <img src="https://www.icegif.com/wp-content/uploads/2022/08/icegif-592.gif" alt="tenet slow" height="200px">
            <h1>Hi awak.</h1>
            <h1>Awak nak jadi girlbestfriend saya tak?</h1>
            <button style="font-size: 25px;" onclick="nak()">nak</button>
            <div id="btn" style="position:absolute; padding: 10px; margin-left: 0; margin-right: 0; left: 0; right: 0; text-align: center;">
                <button style="font-size:25px;" onmouseover="taknak()">taknak</button>
            </div>
        </div>
    </div>
    <script>
        function nak(){
            alert("Yeay! Terima Kasih");
        }
        function taknak() {
            var i = Math.floor(Math.random() * 300) + 1;
            var j = Math.floor(Math.random() * 600) + 1;
            btn.style.left = i + "px";
            btn.style.top = j + "px";
        }
    </script>
</body>

</html>
