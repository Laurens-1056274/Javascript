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