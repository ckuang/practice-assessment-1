### Q1
What is the console output of this code?
````javascript
var arr = [1, 2, 3, 4, 5, 6, 7, 8]
while (arr.length !== 0) {
  console.log(arr.pop())
}
````

### Q2
Write a `div` HTML element with content `Hello World`. Give it an id of `greeting`. Write the CSS to select for that id and assign it the text color of rebeccapurple.

### Q3
Write a `span` HTML element with content `Pikachu`. Give it a class of `pokemon`. Write the CSS to select for that class and assign it the text color of yellow.

### Q4
Write the HTML code for a link that displays `Coalition for Queens` that navigates to http://www.c4q.nyc/.

### Q5
Write a function `wackyCase` that takes a string and returns a string where every odd index is set to uppercase and every even index to lowercase.
````javascript
wackyCase('meow') //returns 'MeOw'
wackyCase('chocolate') //returns 'ChOcOlAtE'
````

### Q6
What gets logged to the console from the code below?
````javascript
var count = 0;

function addCount(){
    var count = 1;
    console.log(count);
}

addCount();
console.log(count);
````

### Q7
Create an object `me` with keys of `name` and `age`. Assign the value of the name key to your name and the age key to your actual age. Write a function `intro` that receives this me object  and returns the string "Hi my name is Charles and I'm 25."
````javascript
intro(me) // returns "Hi my name is Charles and I'm 25."
````

### Q8
Write a function `sumTwoArrays` that receives two arrays and returns the sum of all the elements in both arrays.
````javascript
sumTwoArrays([1, 1, 1, 1], [2, 2, 2, 2]) //returns 12
sumTwoArrays([1, 2, 3, 4], [5, 6, 7, 8]) //returns 36
````

### Q9
Write a function `popShift` that switches the last letter with the first letter in a string.
````javascript
popShift('yellow') //returns 'welloy'
popShift('blue') //returns 'elub'
````

### Q10
Write a function `timesTwo` that receives an array of numbers and returns a new array of every element in the original array multiplied by 2.
````javascript
timesTwo([1, 2, 3, 4]) //returns [2, 4, 6, 8]
timesTwo([3, 1, 10, 2]) //returns [6, 2, 20, 4]
````
