
# Operators and Loops

## WHILE LOOP

- runs an unspecified number of times
- turns off whenever some test expression becomes false. so it's dependent upon a BOOLEAN (T/F expression)
- give it a test expression / condition. True or false? if it's true, while loop keeps running, keep testing. 
- as soon as result is false, breaks out of that loop.
- no idea how long it'll take

## FOR LOOP

- run for a specified amt of time
  - you know you want it to run 5 times 
- goes through **initializing statement** that has a countervariable, keeps count of the variable, how many times you're running it
- then goes through condition, says to keep runnning this while this condition is true.
- if it's true, goes into loop body aka code block.
  - within that statement, the countervariable/ initializer gets incremeneted. (added)
- so the update will increment or decrement the initializing countervariable and goes back into original loop. and on and on...

### EXAMPLE

for (let i = 0; i < 10; i = i++)

3 statements included here:

- initializer statement, sets countervariable to specific number.
    -i is countervariable / index / iterator.
- i" < 10" is conditional statement
    -tells for loop how many times to run. e.g. While incrementer / counter / index is less than 10, this for loop will keep running. 
- increment statement -- adds to the counter variable to move it up a loop.
    -i++ is same thing as "i = i + i"
    -add a +1 every time you get your answer. so runs 10 times until it gets a false

### USE REPLIT

for (let i = 0; i < 10; i++)

    *let i = 0, and while i is less than 10, keep running this for loop.* 

then, define a code block. bc while i is less than 10, we need to run code.

for (let i = 0; i < 10; i++) {
    console.log(i);
}
