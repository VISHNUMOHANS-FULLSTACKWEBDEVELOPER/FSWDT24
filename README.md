# FSWDT24
Day24
<!DOCTYPE html>
<html>
    <head>
        <title>js with html</title>
    </head>
    <body>
        <h3>Js with html</h3>
        <script src="./day24.js"/>
    </body>
</html>
// String manipulation
var data="hey everyone this is js with html session";
console.log("data: ",data);
// slice
console.log("slice:",data.slice(2,4));
// length
console.log("length:",data.length);
// replace
updateddata=data.replace("hey","hi")
console.log("replace: ", updateddata);
console.log("original data:",data);
// includes
console.log(data.includes("is"))
// string to int & int to string
var var1="1234";
console.log(var1);
console.log(parseInt(var1));
var var2=1234;
console.log(var2);
console.log(var2.toString());
console.log(var2.toLocaleString());
// split operator
var var1="gud morning"
console.log(var1.split(" "));
// objects
var var1={
    name:"vishnu",
    Age:21
}
console.log(var1);

var1.name="vishnu mohan";
var1.Age=20;
console.log(var1);
