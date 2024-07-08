<html>
  <head>
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
  </head>

  <style>
    #body1{
        text-align: center;
        
    }
    #btn1{
        font-size: 2em;
        border-style:solid;
        border-radius: 15px;
        border-width: 5px;
        border-color: gray;
        background-color: rgba(0, 255, 0);
    }
    #btn1:hover{
        cursor: pointer;
        background-color: rgba(0, 255, 0, 0.511);
    }
    #btn1:active{
        background-color: aqua;
    }
  </style>

  <body id="body1">
  <h1>Rolling Game</h1>
  <button id="btn1" onclick="click()">Enter</button>
  </body>

  <script>
    const btn = document.getElementById("btn1");
    btn.onclick = function(){
      location.replace("1.html");
    }
  </script>
</html>
