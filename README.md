# MWA Homework 01 - ECMAScript 2015 (ES6)
## Exercise 01
1. Define a removeNum function that will work asynchronously on every Array object. 
   ...The function accepts one argument: a number. 
   ...The function returns a new array after removing all instances of the passed number.
2. Explain how does this function affect the event-loop?
```javascript
console.log('Start'); 
console.log([1, 3, 4, 2, 1, 5].removeNum(1)); 
console.log('Finish'); 
   
Start
Finish
[3, 4, 2, 5]
```
## Exercise 02
1.Create three buttons:
..*Promise Fetch (use Fetch API)
..*Async/Await Fetch (use Async/Await)
..*Reactive Fetch (use Observables)
...When each button is clicked, you will make a request to https://randomuser.me/api/ and return a JSON with name and location only.
2. Explain which one of the three is asynchronous.
