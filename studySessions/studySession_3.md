<img src="http://www.skylabcoders.com/images/403/default.png" alt="Skylab" style="width:200px;height:45px;">
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
g) After that, now, compare with the local hour

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
> Somebody else...? Now we are 1 Beatles

**Second time**
function addBeatle (otherName2){...}
if(total == 4)...";
else(console.log("Somebody else...?"));
console.log("Now we are..." + total +  " Beatles")
> Somebody else...? Now we are 2 Beatles
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
