<!doctype html>
<html>
<head>
<script>
function add(){
var a=0,b=0,c=0,d=0,e=0,f=0,g=0,h=0,i=0,j=0,k=0;
var a1=0,a2=0,a3=0,a4=0,a5=0,a6=0;
a=Number(document.getElementById("first").value);
a3=a3+a;
a4=a4+a;
b=Number(document.getElementById("second").value);
a2=a2+b;
a3=a3+b;
c=Number(document.getElementById("third").value);
a4=a4+c;
d=Number(document.getElementById("fourth").value);
a3=a3+d;
a6=a6+d;
e=Number(document.getElementById("fifth").value);
a4=a4+e;
a5=a5+e;
a6=a6+e;
f=Number(document.getElementById("sixth").value);
a5=a5+f;
a6=a6+f;
g=Number(document.getElementById("seventh").value);
a1=a1+g;
a2=a2+g;
h=Number(document.getElementById("eigth").value);
a1=a1+h;
i=Number(document.getElementById("ninth").value);
a1=a1+i;
j=Number(document.getElementById("tenth").value);
a2=a2+j;
k=Number(document.getElementById("eleventh").value);
a5=a5+k;
arr=[a1,a2,a3,a4,a5,a6];
max=arr[0];
for(i=0;i<6;i++){
    if(arr[i]>max){
        max=arr[i];
    }
}
if(a1==max){
    document.getElementById("answer").value='Civil Engineering';
}
else if(a2==max){
    document.getElementById("answer").value='Mechanical Engineering';
}
else if(a3==max){
    document.getElementById("answer").value='Electronics Engineering';
}
else if(a4==max){
    document.getElementById("answer").value='Electronics and Telecommunication Engineering';
}
else if(a5==max){
    document.getElementById("answer").value='Information and Technology Engineering';
}
else{
document.getElementById("answer").value='Computer Engineering';
}
}
</script>
</head>
<body>
<h1>For each option, give an answer from 0 to 5 from the amount of interest you have in field</h1>
<br>How much do you like to make new electric circuits? : <input id="first">
<br>How much do you like to dismantle and repair electronic circuits? : <input id="second">
<br>How much do you like to study about waves and signals? : <input id="third">
<br>How much do you like to mess with a hardware of a PC? : <input id="fourth">
<br>How much do you like to make softwares and apps? : <input id="fifth">
<br>How much do you like programming? : <input id="sixth">
<br>How much do you like to make new designs for buildings/cars? : <input id="seventh">
<br>How much do you like beautify a new model? : <input id="eigth">
<br>How much would you like to actually build a brand new model? : <input id="ninth">
<br>How much would you like to work with tools? : <input id="tenth">
<br>How much do you like to work with security of a system? : <input id="eleventh">
<br><button onclick="add()">Submit</button>
<br>From your response, the following is the best suited career for you!
<br><br><input id="answer">
</body>
</html>
