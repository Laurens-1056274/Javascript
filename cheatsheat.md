# Cheatsheat
This is a cheatsheat which will contain javascript related logic

## Note
This file will contain typo's because not only is it made for personal use, it's also made
by a Dyslect, my sincire apologies beforehand

## What is Javascript used for?
Javascript is used to make components of a htl file, actually do something. For example:
if you make a calculator using css and html, it still wont function (even tho the calculator looks fine on the webpage). Adding Javascript will make it actually interactible

### console.log()
```console.log("hello world")``` for example, prints hello world in the console (crtl + shift + i and then go to console)
You use this mostly for testing purposes

### window.alert()
```window.alert("This is a alert")``` for example, gives a pop up with the alert: "this is a alert"
You use this to display a simple message to the user. HAndy when a user for example tries to exit your page/delete something

### single line comment
to comment a single line type ```//``` 
A shortcut for commenting code out is selecting the lines, and then pressing crtl + /
you use this (and multiple line comments) to explain what is going on in your code

### multiple line comment
to comment multiple lines type ```/* */```

### document.getElementById(``).textContent = ""
This grabs a specefic id from your html document and changes the textcontent
for example ```document.getElementById(`myH1`).textContent = "hello"``` will get whatever element has the Id "myH1", and give it the text "hello"

### variable
A variable is a container that stores a value. (python example: ```x = 100```, then x is the variable containing the number 100)
In javascript this would be:
```
let x;
x = 100
```
(note, all variable names need to be unique, you can not have 2 times let x; in the same scope )

If you want declaration and assignment in one line:
```let x = 100; ```
You use the former if you want user input/ dont know the value right away

#### use variable in console.log
beneath a example of how to use a variable in the console.log
```
let x = 100;
console.log(`x = ${x}`)
```

### data types
There are multiple datatypes. you can display them by using for example
```console.log(typeof x)```
The types are as followed
    1. number (example: age = 25 (there are no floats in js, so 25.123 is also a number))
    2. strings (example: name = "Eve")
    3. booleans (true or false)

### Intergate variables to html
below a example of how to add the variables to the id of p1, p2, and p3
```
let fullName = "Eve Hill";
let age = 22;
let student = true;

document.getElementById(`p1`).textContent = (`my name is ${fullName}`);
document.getElementById(`p2`).textContent = (`I am ${age} years old`);
document.getElementById(`p3`).textContent = (`I am a student = ${student}`);
```