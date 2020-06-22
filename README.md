# What I Learned Week 5
---

# The Conditional Statements
### if
The `if` statement, like most other languages, is the primary conditional statement of Javascript. If the condition within the parentheses of an `if` statement are equal to `true`, then anything within the brackets will be executed. Otherwise, the code will be skipped over.

An `if` statement is the start of a nest, and while it can be used within another `if` statement, wikk.

### else if
The `else if` statement is dependent upon a prior `if` statement - **IT WILL FAIL OTHERWISE**. It functions similarly run the code within its brackets only when its condition is met - furthermore, it can only be met when the previous `if` statement was false.
This can replace nested `ifs`, allowing more readable code 

You can have multiple `else if` statements within the same nest.

### else
The `else` statement, like the else if, is dependent upon an `if` statement - **IT WILL FAIL OTHERWISE**. Unlike the `if` and `else if`, the else will only act if all of the previous `if` and `else if` condition were false.
The `else` does not have a conditional statement, and only runs as stated above. 
This makes it very useful for default cases and error handling.

You may only have one `else` statement per nest.

---

### Switch
The `switch` statement takes in a value, and tests it to see if it matches any of the following `case` conditions. Upon doing so, it will run the appropriate `case` processes.
The proper way to set up a switch statement: 
`switch(x) {` 

    default:
        //code
        break;
    case a:
        //code
        break;
    case b:
        //code
        break
`}`

The `default` case runs when no other `case` condition is met. This makes it useful for error handling and, oddly enough, default cases.

---

### Math.random()
`Math.random` is the statement in Javascript used to generate a random number. By using it this way, it will generate a random number between 0 and 1.
You can use it in this formula: `(Math.random() * maxNumber) + minNumber` to create a range of which you want a random number to be generated.
For example, if you wanted to generate a number between 1 and 10, you would do this: `(Math.random() * 10) + 1`. 
To ensure that you get an integer value, it is best to use it within a rounding statement as well.