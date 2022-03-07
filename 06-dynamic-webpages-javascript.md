# Dynamic Web Pages with Javascript

## Variables
-like a container for some content. Way to refer to elements that may take up more code space. Usually semantics, affects readability of code.
>var, let, const = all variables

Use " var "

    -all variables must have unique identifiers
  
    -names can contain letters, digits, underscores, dollar signs but must begin with a letter.
   
    case sensitive
    -var button = document.querySelector('button');

    -var box = document.getElementById('changeme')

    -equal sign = assigns.
    
    -to say "equal to," it's double ==

    camelCase

### Strings
-text values like "John Doe"
-can be double or single quotes
-if you put a number in quotes, treated as a string

Boolean
-T/F condition?

THE DOM
-Document Object Model
-programming interface that allows you to manipulate HTML, CSS
represents the document as nodes and objects; that way, programming languages can interact with the page

let userName = "Elizabeth";
console.log(userName);

> in console log = Elizabeth

- "let" tells javascript that this is a variable. Variable like a bucket, holding a value. Value that it's holding = STRING.

### PROMPTS -- calling a function
> Built-in method in javascript that allows us to ask the user for something.

prompt("What is your name?")
> put inside string because you're expecting to ask something
> take that user input and do something with it (display it in an h2 on my dom). In order to save "Elizabeth," you have to save that prompt into a variable:

let (or var) myName = prompt("What is your name?")
console.log("myName: ", myName)

document.write(myName)

### CONDITIONAL STATEMENTS

will return one of two things: yes or no; true or false; on of off, etc.

- returns a boolean 