<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .koleso{
        margin-top: 50px;
        height: 50px;
        width: 50px;
        background-color: #161313;
        border-radius: 50%;
        transform: translate(5px, 190px);
        animation-duration: 6s;
        animation-name: carr;
        }
        .koleso2{
        margin-top: 70px;
        margin-left: 130px;
        height: 50px;
        width: 50px;
        background-color: #161313;
        border-radius: 50%;
        transform: translate(5px, 70px);
        animation-duration: 6s;
        animation-name: koles;
        }
        .korpys{
            border-radius: 15px;
            height: 50px;
            width: 200px;
            background-color: #d1b61c;
            animation-duration: 6s;
            animation-name: carr;
        }
        .glass{
            height: 39px;
            width: 5px;
            border-radius: 35px;
            background-color: #23e5f359;
            transform: translate(150px, -80px) rotate(-30deg);
            animation-duration: 6s;
            animation-name: carr;
            
        }      
        .sit{
            height: 20px;
            width: 5px;
            border-radius: 5px;
            background-color: black;
            transform: translate(110px, -107px) rotate(-20deg);
            animation-duration: 6s;
            animation-name: carr;
        }   
        @keyframes carr {
  from {
    margin-left: 5%;
    
  }

  to {
    margin-left: 77%;
    
    
  }
}
@keyframes koles {
  from {
    margin-left: 5%;
    transform: translate(130px, 70px);
  }

  to {
    margin-left: 77%;
    transform: translate(130px, 70px);
    
  }
}
  </style>
</head>
<body>
    
    <div class="koleso"></div>
    <div class="koleso2"></div>
    <div class="korpys"></div>
    <div class="glass"></div>
    <div class="sit"></div>
</body>
</html>








<!-- 
linear: линейная функция плавности, изменение свойства происходит равномерно по времени   display: inline-block;-->
