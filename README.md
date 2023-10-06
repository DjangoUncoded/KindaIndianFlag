<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
.orange{
    background-color: orange;
    height: 200px;
    width: 900px;
    position: relative;
}
.orange>div{
    background-color: green;
    position: absolute;
    height: 200px;
    top: 400px;
    width: 100%;
}
.orange>div>div>p{
    background-color: rgb(3, 3, 104);
   
      position: absolute;

      height: 200px;
      width: 200px;
      border-radius: 50%;
      bottom: 184px;
      left: 350px;
    
}
.flag>div>div{
  background-color: white;
  height: 200px;
  width: 900px;
  margin-top: 200px;
  position: relative;
}



    </style>
</head>
<body>
    <div class="orange">
        <div>
            <div>
                <p> 

                </p>
            </div>
        </div>
    </div>
    
</body>
</html>
