# simple-function-script
JavaScript quick challenge

// The challenge was to:
// Define a function named greet that takes 2 arguments

// firstName (string)
// lastName (string)
// Return a string in the format 'Hello, Kelly Rippa!' using these arguments
// 🌟 Bonus: Use a template string to do this! ( i have not learned how to do this yet...)

// My hard learned script became what is below ( and it worked... :o )

function greet(firstName, lastName) {
  firstName = "Kelly";
  lastName = "Rippa";
 return firstName + " " + lastName;
}
var b = greet ();
console.log("Hello, " + b + "!");

// create a function that accepts 2 parameters
// a first name, and a last name
// and prints the first name and last name together in the console
// saying "Hello, Fname Lname!"
// hint: string concatenation

// with template literals
function helloFnameLname(a, b){
  console.log(`Hello, ${a} ${b}!`);
};
helloFnameLname('Kelly', 'Rippa');

// with standard quotes
function helloFLname(a, b){
  console.log('Hello, ' + a + ' ' + b + '!');
};
helloFLname('Johnny', 'McJohnny');
