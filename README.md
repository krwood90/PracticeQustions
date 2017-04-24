# PracticeQustions
Java


1.What value is now stored in the variable name? 
isKing



2. What is the difference between == and === in Javascript?
== is abstract vs === is strict. like 3 == "3" true vs 3 === "3" false



3.Write a function that takes two numbers as arguments and returns the sum of the two numbers in Javascript

```javascript
function(a,b){
return a + b
```


4.Write a function that takes an array as an argument and prints out the numbers 
in the array that are greater than 5 (for example foo([3,6,1,7]) 
would print out 6 and 7) in Javascript

```javascript
foo([3,6,1,7])
function array()
for ( var i = 0; i < foo.length; i++) {
if ( foo[i] > 5) {
console.log(foo[i]);
}
};
else {
};
```



5.Write a for loop that will iterate from 0 to 20. For each iteration, 
it will check if the current number is even or odd, and report that to the screen in Javascript

```javascript
array[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20]
for(var i = 0; i < array.length; i++) {
if(array[i] % 2 == 0) {
console.log(array[i]);
}
else {
console.log(array[i])
}
};
```



6.What does 'this' refer to when used in a JavaScript method?
this. refer to the owner of the function being executed.




7.Create an object that has properties with name = "fred" and major="music" and a property 
that is a function that takes 2 numbers and returns the smallest of the two, or the square of the two if they are equal.

```javascript
var fred = {major: music}
fred.sum = function(a,b) {
if(a < b){
return a;
}else(a > b){
return b;
} else if(a = b){
return a*b;
}
};

```


8.What’s the result of executing this code and why? 

```javascript
The resultfunction test() {
   console.log(a);
   console.log(foo());
   
   var a = 1;
   function foo() {
      return 2;
   }
}

test(); 
```
is 1 because the script never reachs the function assignment before solving
but the (var a = 1) gets moved up so it solves for that.




9.Write a function to print out the song lyrics to "99 Bottles of Beer." 
Now add a case for when there are no bottles left.

```javascript
var bottles[99, ..., 0]
function (){
for (var i = 0; i < bottles.length; i++){
if(bottles[i] = 0){
var case = [12, ..., 0]
bottles.push = case
};
}
console.log([i] + " bottles of beer.")
};
```



10.Write a function to mimic the game of Exploding Kittens using a standard 52 card deck 
with a single joker. Deal a random card to each player each turn. The game ends when 
someone is dealt the joker. Display a dialogue message to the losing player.

```javascript
var deck= [1, ..., joker, ..., 52]
function() {
for( var i = 0; i < deck.length; i++){
if([i] = joker){
console.log("you drew the Joker, you lost.")
}else{
}
}
};
```







# Count The Fives

*
*Explanation:** Create a function the takes an Array of numbers and returns an Integer count of the number of 5's in the Array

*
*Bloc Objective:** Write a for loop.

*
*Content:*
*

```javascript

// Create a function the takes an Array of numbers and returns an

// Integer count of the number of 5's in the Array




function countFives(numbers) {

for( var i = 0 ; i <= countFives.length; i++){

var count = 0

if (i == 5);

count++;

}

}
console.log("There are " + count + " 5's in the array.")




countFives([5, 6, 2, 5, 9, 3, 5]);

//=> 3


countFives([5, 6, 2, 5, 9, 3, 5, 4, 6, 7, 5, 4, 5, 5]);

//=> 6
```









