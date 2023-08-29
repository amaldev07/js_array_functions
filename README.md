# js_array_functions
let a  = [1,2,3];
a.shift(); // removes the first element from begining //a: [2,3] 
a.unshift(12) // add 12 to first //a: [12,2,3]
a.push(4); // add element to last // a: [12,2,3,4] 
----------------------------------------
To get the last element from an array
array.pop()
this will return the last element from the array - and remove the last element from the array
let fruit = ['apple', 'orange', 'banana', 'tomato'];
let popped = fruit.pop();
// popped: 'tomato'
after this operation 'tomato' will be removed from the array 
so the array become as below
// fruit : ['apple', 'orange', 'banana'];
------------------------------
create an array with 26 elements and fille with 0 values
let ar = new Array(26).fill(0);
