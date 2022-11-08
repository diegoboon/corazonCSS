# corazonCSS

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corazon</title>
    <link rel="stylesheet" type="text/css" href="style.css"/>
    <style>
    .divCorazon{
    margin: auto;
    padding: 10px;
    text-align: center;
    margin-top: 10%;
    animation: divCorazon 1s ease infinite;
}

@keyframes divCorazon {
    0% {
      transform: scale(1, 1);
    }
    50% {
      transform: scale(1.5, 1.5);
    }
    100% {
      transform: scale(1, 1);
    }
  }
.corazon {
    background-color: red;
    display: inline-block;
    height: 30px;
    margin: 0 10px;
    position: relative;
    top: 0;
    transform: rotate(-45deg);
    width: 30px;
    
  }
  
  .corazon:before,
  .corazon:after {
    content: "";
    background-color: red;
    border-radius: 50%;
    height: 30px;
    position: absolute;
    width: 30px;
  }
  
  .corazon:before {
    top: -15px;
    left: 0;
  }
  
  .corazon:after {
    left: 15px;
    top: 0;
  }
    </style>
</head>
<body>
    <div class="divCorazon">
    <span class="corazon"></span>
</div>
</body>
</html>
