<html>
<head>
<meta http-equiv="Content-Type"
content="text/html; charset=windows-1251">
<title>Стили</title>
</head>
<body>
<script>
var A=0;
var arr=['15'];
min=0;
max=1;
function er2(){

b=0
  while (b <= 15) {  
  arr[b]=min + (Math.random() * ( max - min));
    b++;
}
A++;
change_number()


document.getElementById("inf1").innerHTML=document.getElementById("inf1").innerHTML+" Элемент"+(A-1)+ " "+arr[A-1]+"<br>";
}

function change_number(){
document.getElementById("inf2").innerHTML="Задайте "+ A+"ый элемент массива"+'<input type="text" value="a" id="mark">'};


function er1(){
var fruits = ["A","B","C","D","E","F","G","H","I","J"];
document.getElementById("inf1").innerHTML=fruits;
}



  
  
  
  
  

</script>
<button onclick="er1()">11.1!</button>
<br>
<button onclick="er2()">11.2!</button>
<br>
<button onclick="er3()">11.3!</button>
<br>
<div id = "inf2">Задайте 0ой элемент массива <input type="text" value="a" id="mark"></div>
<br>
<div id = "inf3">Массив со "случайными" значениями <input type="text" value="a" id="mark"></div>
<div id="inf1"></div>
<br>
</body>
</html>
