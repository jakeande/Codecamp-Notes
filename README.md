#Codecamp Notes

Lesson notes for LaunchCode
CODING COUNTING STARTS AT ZERO 

#Errors
NameError: name 'wait_time_int' is not defined on line 5




#what type of error
    -ParseError
        = Syntax errors, missing characters
            -TokenError(EOF) = went to the end of the file and need something to end a line
    -TypeError
        = usually when you try to add a str to a int or a float to str
    -NameError
        =Something is named wrong, spelled wrong
    -ValueError
        =Ocur when you pas a parameter to a function and hte function is expecting a certain type but you pass it a different type 
    Loops and iteration
        - in order to repeat a task, we need two things
            1. task that should repeeat
            2. data set that should be used with the task
    - loops alllow 
    - for(key word) ______ in (key word)loop body[list]: 
        -->print (____)
    - try to make singuluar name then a pleril name for the list
    Range function
    - print(range(5))
        = [0,1,2,3,4]
        - 5 equals the number in the list
        - start - the first number in the list
        - stop - on more than the last number
        - step - how much do we count by
        -range(5,10)
            - starts at 5 and finishs at 9
        -range(0, 101, 2)
            - starts at 0 and counts all evens
        -range(100, -1, -2)
            -  starts at 100 and counts backward to zero by twos 
Turtle
Method	Parameters	Description
Turtle	None	Creates and returns a new turtle object
forward	distance	Moves the turtle forward
backward	distance	Moves the turtle backward
right	angle	Turns the turtle clockwise
left	angle	Turns the turtle counter clockwise
up	None	Picks up the turtles tail
down	None	Puts down the turtles tail
color	color name	Changes the color of the turtle’s tail
fillcolor	color name	Changes the color of the turtle will use to fill a polygon
heading	None	Returns the current heading
position	None	Returns the current position
goto	x,y	Move the turtle to position x,y
begin_fill	None	Remember the starting point for a filled polygon
end_fill	None	Close the polygon and fill with the current fill color
dot	None	Leave a dot at the current position
stamp	None	Leaves an impression of a turtle shape at the current location
shape	shapename	Should be ‘arrow’, ‘classic’, ‘turtle’, or ‘circle’

attribute
Some state or value that belongs to a particular object. For example, tess has a color.
canvas
A surface within a window where drawing takes place.
control flow
See flow of execution in the next chapter.
deterministic
A process that is repeatable and predictable.
documentation
A place where you can go to get detailed information about aspects of your programming language.
for loop
A statement in Python for convenient repetition of statements in the body of the loop.
instance
An object that belongs to a class. tess and alex are different instances of the class Turtle
invoke
An object has methods. We use the verb invoke to mean activate the method. Invoking a method is done by putting parentheses after the method name, with some possible arguments. So wn.exitonclick() is an invocation of the exitonclick method.
iteration
A basic building block for algorithms (programs). It allows steps to be repeated. Sometimes called looping.
loop body
Any number of statements nested inside a loop. The nesting is indicated by the fact that the statements are indented under the for loop statement.
loop variable
A variable used as part of a for loop. It is assigned a different value on each iteration of the loop, and is used as part of the terminating condition of the loop.
method
A function that is attached to an object. Invoking or activating the method causes the object to respond in some way, e.g. forward is the method when we say tess.forward(100).
module
A file containing Python definitions and statements intended for use in other Python programs. The contents of a module are made available to the other program by using the import statement.
object
A “thing” to which a variable can refer. This could be a screen window, or one of the turtles you have created.
pseudo-random number
A number that is not genuinely random but is instead created algorithmically.
random number
A number that is generated in such a way as to exhibit statistical randomness.
random number generator
A function that will provide you with random numbers, usually between 0 and 1.
range
A built-in function in Python for generating sequences of integers. It is especially useful when we need to write a for loop that executes a fixed number of times.
sequential
The default behavior of a program. Step by step processing of algorithm.
standard library
A collection of modules that are part of the normal installation of Python.
state
The collection of attribute values that a specific data object maintains.
terminating condition
A condition that occurs which causes a loop to stop repeating its body. In the for loops we saw in this chapter, the terminating condition has been when there are no more elements to assign to the loop variable.
turtle
A data object used to create pictures (known as turtle graphics).
              
List
        - in python is a data structure that allows us to collect several values in single variable or value
            [   ]
                - we can store a list in variable
                - list define a new type:
                    -print(type(retired_num...))
                    -output: <type 'list'>

    bolion 
        - True or false


introduction to functions
    print
    input
    range
    - will return data
        =RETURN VALUE
    Defining a Function
    - We can write our on function
        = def my_function( parameter ):
            # function code, with our with out a return value
            exp: def hello_world():
                    return "hello_world()
                message = hello_world()
                print(message)    
            exp with pararmeter: def hello_world(name):
                                    return "Hello" + name
                                    message= hello_world                                        ("sally")
                                    print(message)
                                    output: Hello Sally
Modules
- in python is a collection of pyton code that is bundled up for others to use, but which is not part of the core python programming language
we must install and then import them
    REAL CODING ENVIRONMENTS
        - installin a module requires a program like pip or conda. 
        - package repositoriees
-USING MODules
    - for a module that is available, it can be used within a program by importing module
        import math
         - the identifier math is now available for us to usewithin oour file
            pring(math.pi)
            output: 3.14
The Python REPL
READ EVAULAUTE PRINT LOOP



Functions
= is named sequence of statements that carry out a specific task.
    Defining a functions
        -   we can define our own function
        = def my_function( parameter ):
            # function code, with our with out a return value
            exp: def hello_world():
                    return "hello_world()
                message = hello_world()
                print(message)    
            exp with pararmeter: def hello_world(name):
                                    return "Hello" + name
                                    message= hello_world                                        ("sally")
                                    print(message)
                                    output: Hello Sally
            - once we have made our own function
                - gives us the oppurtunity to reuse the code
                    -takes away from errors 
                - Its IDEAL to incapcelate programs, to clean up your code and make it less DRY
        - A code within in a function will not run intell we actually run the function
      A.  def add_two(num):
            return(num + 2)
            print("after return statement")
    
         print(add_two(2))
         ^ for example the if you ran the add_two function the number would do absolutely nothing.
            - A return statement finishs the function

        - Terminology
            -when you run a program it --> (return statement)
        Visualing a Function
            parameter(S) -> function -> Return value

        IN A FUNCTION
            - you can always return one "value"  even if it is a list 

    Question through lecture
    1. does a function have to have parameters?
        -   NO. does not need 
    2. What happens if you have two variable (0,0)
        -   Yes. A function can mutliple parameters
            - Can make an opsional parameter
                - (a, b=0)
    2. what happens if we call a function without providing for one or more input parameters?
        -   in error accurs 
    3. Does a function have to return a value?
        -   No. depends on what the function should do 
    4. What happens if we have a function that doesn't reutrn a value, but we try to store a return value in a variable?
        -   when we try to store it in a variable
            if the function says print it will just print the message. 
            if you use the print function 
                = it will reuturn (none)
        - the value that is implicitely returned and stored is the "special value none

None = is a varaible and will tell python that there is nothing in it. 

Scope
    - all variable and parameters within a program have a scope. their scope determines how they may be accessed and used.
        exmp:
            def add_two(num)       
                num = num + 2

            add_two(2)
            print(num)
                        notes: you can not define something that is in a function
    Local Scope
        - variable and parameters within a function have local scope. they may only be accessed within the function in which they are defined. 
            we call such variable local variables.
                result is a local variable
    Global Scope
        - variables and parameters that are not defined within a function have global scope. they may be accessed from anywhere within the given file or program. 

            num = 2

            def print_num():
                print(num)
            print_num()

    Shadowing
        - what hpapens whne we use the asame name for a global vaiable and local variable?
            num = 2

            def print_num(num):
                print(num)
            print_num(3)
            - the num that is inside the function will hide the on that is out side the function but if you are outside of the function you will get 2. 

chapter 5 glossary
chatterbox function
A function which interacts with the user (using input or print) when it should not. Silent functions that just convert their input arguments into their output results are usually the most useful ones.
composition (of functions)
Calling one function from within the body of another, or using the return value of one function as an argument to the call of another.
dead code
Part of a program that can never be executed, often because it appears after a return statement.
fruitful function
A function that yields a return value instead of None.
incremental development
A program development plan intended to simplify debugging by adding and testing only a small amount of code at a time.
None
A special Python value. One use in Python is that it is returned by functions that do not execute a return statement with a return argument.
return value
The value provided as the result of a function call.
scaffolding
Code that is used during program development to assist with development and debugging. The unit test code that we added in this chapter are examples of scaffolding.
temporary variable
A variable used to store an intermediate value in a complex calculation.

Using a main function
    -   main block _main_
        - test code by calling it over and over again
        
#Styles
    -   use 4 spaces for indentation
    -   imports should go at the top of the file
    -   separate function definitions with two blank lines
    -   keep function definitions together
    -   keep top level statements, including function         calls, together at the bottom of the program
        
Making Decisions with Conditions
Making decisions
    - conditions
        -true  and false
            - true do this
            - false do that
    Booleans
        = boleans are special data types (bool in python) that signify True and FAlse
            - must be capitalized
            - are not strings; True is different from "true"
            - Are the result of certain arithmatic comparison expressions
                print(type(True))
                IS A TYPE
        -combine boolean values in ways using (and, or and not) that match our natural language usage of combining different conditions
    IF/else statements
        -  if (conditions):
                code block # 1
        -   else:
                code block # 2
        -   Elif:
                can check a bunch of stuff in on if else clause. 
        if/else statements
            - only exacutes what ever is true first.
        