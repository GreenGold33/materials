<img src="http://www.skylabcoders.com/images/403/default.png" alt="Skylab" style="width:200px;height:45px;">
## Pre-Curs SkyLab Coders ~60 exs. 
### Study sessions (Strings, Loops, Conditionals)
### Ex. 1 - Strings 

**Exercise**: *Identify yourself, who are you?*

a) Define a **string var** with your name 
b) Now, show your name in **console terminal**

```
> console.log(name);
'name'
```

c) Fine, now, define a var with your age and **show your age and name** also using the console

```
> console.log(name + age);
'name , age'
```

d) Pass this vars as parameters in a **function** that shows them on the console

```
> showMyData("alex", 25);
alex 25
```

e) Now, show your info with a pretty **presentation message**

```
> showMyData("alex", 25);
My name is alex and I'm 25 years old
```

f) **Add** a new parameter to the function for your current city, Can you **RETURN** the updated presentation message?

```
> var myData = showMyData("alex", 25, "barcelona");
> console.log(myData);
My name is alex, I'm 25 years old and I live in barcelona
```
_Hint: test your function w/ different values_

g) Modify your function to receive data in an **array**. Should return the same

```
> var myData = showMyData(["alex", 25, "barcelona"]);
> console.log(myData);
My name is alex, i'm 25 years old and i live in barcelona
```

h) Modify your function to return the string **"ERROR!"** if second parameter is not a number

```
> var myData =  showMyData(["alex", bbbbb, "barcelona"]);
> console.log(myData);
ERROR!
```

_Hint: `typeof( ANY_NUMBER )` returns the string "number"_ 

i) Modify your function to receive values in a string **separated by '|'**. Should return the same (also the error logic)

```
> var myData = showMyData("alex|25|barcelona");
> console.log(myData);
My name is alex, I'm 25 years old and I live in barcelona

> var myData = showMyData("alex|aaaaa|barcelona");
> console.log(myData);
ERROR!
```

j) Add a new function to your program **that insert a new value** in the array, asure the changes are completed in console.

```
> function addValue(value)
> console.log(array)
'value1, value2, value3...' <- updated
```

k) Now, after insert some new values, modify the function for return the array values **separated by '&'**.

```
> console.log(array);
value1 & value2 & value3...
```
