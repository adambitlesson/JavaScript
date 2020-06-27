# 视频体验

1.Create Folder

2.Link External JavaScript File

```text
<!DOCTYPE html>
<html>
<body>

<button type="button" onclick="myFunction()">Click to see change bellow!</button> 
<p id="test">This is an oringinal paragraph.</p> 

<script src="js/scripts"></script>
</body>
</html>

<script> function myFunction() {    
document.getElementById("test").innerHTML = "See! I am changed now!"; 
} 
</script> 
```

3.JavaScript in internal file

```text
<!DOCTYPE html>
<html>
<body>

<button type="button" onclick="myFunction()">Click to see change bellow!</button> 
<p id="test">This is an oringinal paragraph.</p> 

<script> function myFunction() {    
document.getElementById("test").innerHTML = "See! I am changed now!"; 
} 
</script> 
</body>
</html>
```

4.JavaScript Object Simple example

```text
<!DOCTYPE html>
<html>
<body>

<p id="test"></p>

<script>
var student = "Adam";
document.getElementById("test").innerHTML = student;
</script>

</body>
</html>
```

5.Create JavaScript Object Student - with properties: name value pairs

```text
<!DOCTYPE html>
<html>
<body>
<p id="test"></p>
<script>
var student = {
  firstName : "Adam",
  surName  : "Bitlesson",
  age     : 55,
  hairColor  : "black"
};
document.getElementById("test").innerHTML = 
student.firstName + " " + student.surName;
</script>

</body>
</html>
```

6.Learn JavaScript 6 Use Keyword new to create object

```text
<!DOCTYPE html>
<html>
<body>
<p id="test"></p>

<script>
var student = new Object();
    student.firstName = "Adam",
    student.surName = "Bitlesson",
    student.age = 55,
    student.hairColor = "black"
document.getElementById("test").innerHTML =
student.firstName + " " + student.surName;
</script>
</body>
</html>
```



7.Easy way to create object

```text
<!DOCTYPE html>
<html>
<body>
<p id="test"></p>
<script>
var student = {firstName: "Adam", surName: "Bitlesson", age: 55, hairColor: "black"};
document.getElementById("test").innerHTML = student.firstName + " " + student.surName; 
</script>

</body>
</html>
```

8.Objects are mutable

```text
<!DOCTYPE html>
<html>
<body>
<p id="test"></p>
<script>
var student = {firstName: "Adam", surName: "Bitlesson", age: 55, hairColor: "black"};

var a = person;
a.age = 20;
document.getElementById("test").innerHTML = student.firstName + " is " + student.age; 
</script>

</body>
</html>
```



9.JavaScript Function Declarations

```text
<!DOCTYPE html>
<html>
<body>
<p id="test"></p>

<script>
var x = myFunction(2,5);
document. getElementById("test").innerHTML = x

function myFunction(a, b) {
    return a * b;
}
</script>

</body>
</html>
```

10.JavaScript Function Expressions

```text
<!DOCTYPE html>
<html>
<body>
<p id="test"></p>

<script>
var x = function (a,b) {return a * b}
document. getElementById("test").innerHTML = x(9, 9)

</script>

</body>
</html>
```



