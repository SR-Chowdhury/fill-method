### Definition and Usage of fill () method
* The fill () method fills specified elements in an array with a value.
* The fill () method overwrites the original array.
* Start and end position can be specified. If not, all elements will be filled.

### Syntax
array.fill (value, start, end)

### Parameters
* value	Required -> The value to fill in.
* start	Optional -> The start index (position). Default is 0.
* end	Optional. -> The stop index (position). Default is array length.

### Return Value
An array (the filled array)

~~~
<!DOCTYPE html>
<html>
<body>

<p id="demo"></p>

<script>
  const fruits = ["Banana", "Orange", "Apple", "Mango"];
  document.getElementById("demo").innerHTML = fruits.fill("Lemon, 2, 4");
</script>

</body>
</html>
~~~

### Output: Banana,Orange,Lemon,Lemon

Example: https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_fill

