# 6602482-Nattapol.github.io
WebTest


<!DOCTYPE html>
<html>

  <head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">

    <title>A very simple example</title>

    <style>

      .description {
        padding-top: 40px;
        font-weight: bold;
      }

    </style>

    <script>

      function start() {
        setInterval(function() {
          const red = Math.floor(Math.random() * 256) + 1;
          const green = Math.floor(Math.random() * 256) + 1;
          const blue = Math.floor(Math.random() * 256) + 1;
          document.getElementById("myHeading").style.color =
            `#${red.toString(16)}${green.toString(16)}${blue.toString(16)}`;
        }, 250);
      }

    </script>

  </head>

  <body onLoad="start();">

    <h1 id="myHeading">Welcome To my GitHub </h1>
    <hr />
    <div class="description"> * Nattapol Jompapin</div>
    * University of Phayao 
    * Student 66 
    * </div>

  </body>

</html>
