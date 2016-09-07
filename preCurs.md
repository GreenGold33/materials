<img src="http://www.skylabcoders.com/images/403/default.png" alt="Skylab" style="width:200px;height:45px;">
## Pre-Curs SkyLab Coders ~ 40 exs. 
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

---

### Ex. 2 - Loops

**Exercise**: *Counter*

a) We want to do a counter, from 0 to 5.

```
> for (var i = num; i >= 0; i++) **SHOW NUMBERS** };
0
1
2
3
4
5
```

b) You can add a message when the count is over?

```
0
.
.
.
5
COUNT FINNISH!
```

c) Now we want to increase the count to 10.
d) You can do the same, but with an array?

```
> var array = [0,1,2,3,4,5]
> for(...){**SHOW NUMBERS**}
0 
1 
2 
3 
4 
5
```

e) So, how about create a friend list? Change the array values for your friends names and show in console.

```
> var array = [name1, name2, name3, ..., nameN]
> for(...){**SHOW NAMES**}
name1
name2
name3
.
.
.
nameN
```

f) Now we want add a number, show for console the array position of your friends behind their names.

```
> var array = [name1, name2, name3, ..., nameN]
> for(...){**SHOW NAMES**}
name1 - nº 1
name2 - nº 2
name3 - nº 3
.
.
.
nameN - nº N
```

g) You can add a last friend into a array? Show the updated array for console.

```
> var array = [name1, name2, name3, ..., nameN]
> for(...){
> array.addFriend()...
> **SHOW NAMES**
> }
name1 - nº 1
name2 - nº 2
name3 - nº 3
.
.
.
nameN - nº N
nameN +1 - nº N+1
```


h)<a name="fibo"></a> **FINAL!**We turn back to numbers...
So, we want do a sumatory, the next number in count must sum to previously number

```
NºINICI = 0;
0 (NºINICI+0)
1 (0+1)
3 (1+2)
6 (3+3)
10 (6+4)
```

i) You can add the position of all sums?

```
0, pos 0
1, pos 1
3, pos 2
6, pos 3
10, pos 4
```

j) create a loop for show in console the results from 0 to 50 in 5 to 5.

```
> for(...){**SHOW NUMBERS**}
0 
5
10
15
20
.
.
.
50
Finnish!
```

k) Now, modify your program for shows the results to 0 to 100, in 10 to 10.

```
> for(...){**SHOW NUMBERS**}
0
10
20
30
40
.
.
.
100
Finnish!
```

---

### Ex. 3 - Conditionals

**Exercise**: *If...*

a) Let's start with simple exersice, declare your name, if your name is bigger than 8 letters, show a message

b) Add your lastname and compare separated

c) Now, compare between they and show who is bigger.

d) CAlCULATOR. Multiply two numbers, so, compare the result with IF conditionals, if the result is > 10, show a message, if is < 10, show other message

```
function(n1, n2){
...
    if(res > 10){...)
        }else if(res < 10){..);
    }
}
```


e) Then, what happen if we multiply 5*"word"? The result is NaN (Not a Number), then we can control this error with other conditional, right? Let's do this.

http://www.w3schools.com/jsref/jsref_isnan.asp  <- Method isNaN

*Hint: if(isNaN(res)==true)*

f) CLOCK. Let's do other simply program that you pass one param. to a function, and the IF conditionals should print a message saying: Good morning/afternoon/night

```
function(hour){
    if(...){
    console.log("say something")
    } else if{console.log("say other thing")}...
}
```
g) After that, Now, compare with the local hour

http://www.w3schools.com/jsref/jsref_obj_date.asp

```
var d = new Date(); //declare a new native javascript object (Date)
var n = d.getHours(); //and catch what this object can offer to us
...
if(...){
    console.log("the specify hour is after now")
}else{console.log("the specify hour is before now")}
```

h) **IF** the specify hour is equal to local hour? Control this exception! 

```
...
else if(...){...)}
...
```

i) BEATLES. Now we want to make a program that we specify the members of the Beatles, if are all the Beatles in the array, show "We're all!", if you specify 3 Beatles for example, say other thing.

```
var beatles = ["a","b","c","d"];
if(){
    ...
}
> We're all!

```

j) Now, declare an empty array and do a function that **PUSH** the names of all Beatles, the conditional IF **should** return "We're all!".

http://www.w3schools.com/jsref/jsref_push.asp <- Push Method

```
function(name,name2...){
    ...
    if(...){
    ...
    }else{console.log("something failed")}
}
```

k) Make other program that **push** all Beatles, when the four Beatles are in array, show a message, if the length of a array are < 4, show a message that say to user: Continue writing the names! 
*REMEMBER: Control the number of Beatles are in array after execute the function for sure you're pushing the names properly.*

**Hint: Make a empty array and push the results!**
```
**First time**
function addBeatle (otherName1){...
    if(total == 4)...";
        else(console.log("Somebody else...?"));
}
console.log("Now we are..." + total +  " Beatles")
> Somebody else...? Now we are 1 Beatle

**Second time**
function addBeatle (otherName2){...}
if(total == 4)...";
else(console.log("Somebody else...?"));
console.log("Now we are..." + total +  " Beatles")
> Somebody else...? Now we are 2 Beatle
.
.
.
```

l) ALEATORIO. Create a function that randomize a number and specify if the number are above or under the half of the maximum.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random  <- Random method of Math Object

**Hint: var val = Math.floor(Math.random()*max)+min;** 
```
> function aleat(max,min) {
>    var val = Math.floor(Math.random()*max)+min;
> ...
> }
*ej. Si el numero random es 20 y el numero max es 30*
out:
El numero 20 está por encima de la mitad(30 / 2)
```

m) **Challenge!! - Simple Scripting program**. Create a program that transform a 4 number values code to diferents positions, making a new code.
Something like: 
3712 
:point_down:
7123
:point_down:
1237
:point_down:
2371
The first, go to the last position, second, third and four goes up.

*Hint:* Is necessary use FOR, IF and Array technolgies seen in precourse.

n) **Super-Challenge!!**
Create a program that use the Roman form for encrypt messages, how is that? Simple. If you have SKYLAB, the encrypted form is  SLKYAB...
If you divided the word in two groups of 3 letters, you get:
SKY
|-|-|
LAB 
Then, join the S with L, K with A and Y with B, and you get SLKYAB.

So, make a program that, receive the message SLKYAB and returns the SKYLAB.

ñ) **You got it?** Then try now with SKYLABCODERS. 

---

## HTML & CSS MARKUP

http://www.w3schools.com/tags/ <- List of all tags of HTML lenguage


![snapshot](img/html.png)
*Basic estructure for HTML main page*


####Exercise: 
Do the semantic markup for the following image(**no styles**, only semantic HTML).

![snapshot](img/shot1.png)

---


![snapshot](img/shot2.png)

####Exercise: JS Script
We learn about Javascript and HTML-CSS basic, how they are relacionated? 

http://www.w3schools.com/js/js_whereto.asp 

Make a JS script in HTML page, that execute a script, this script cath two numbers and get the sum, rest, mult and div for console.

Now, you can insert the results in a table?

http://www.w3schools.com/cssref/css_selectors.asp

As a final challenge, you remember the [Fibonacci](#fibo) ?
Instert the values in a table from 0 to 15 loop.

---











