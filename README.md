# vocab

# V

__Vocabulary__: 
 
 Week 1 
* Expressions : Lines that evaluate to a single value 
* Operators : Take in one or more values and produce a new one. These 'compose' to create expressions
* Operator Precedence : The order in which JavaScript evaluates composed operators
* Type Conversion (or Coercion) : Changing the type of a value or a type of an operator

* UNARY AND BINARY OPERATORS
    A unary operator is one that takes a single operand/argument and performs an operation. e.g. delete
    A binary one takes two operands. e.g. remainder

* PRIMITIVE METHODS
    A JavaScript method is a property containing a function definition.

* VARIABLES
    Containers for storing data values

* GLOBAL SCOPE
    A global variable has global scope: All scripts and functions on a web page can access it.

* BLOCK SCOPE
    When defining using let and const: scoped to the function they are scoped to the block.
    What is the block? A block is a set of opening and closing curly brackets.

* PARSING 
    Usually part of a compiler,the method of receiving an input in the form of sequential source program instructions, interactive online commands, markup tags, or some other defined interface and breaks them up into parts that can then be managed by other programming.

* STATEMENT VS EXPRESSION
    An expression produces a value and can be written wherever a value is expected, for example as an argument in a function call. 
    For example:
    myvar
    3 + x
    myfunc("a", "b")
    Roughly, a statement performs an action. Loops and if statements are examples of statements. Wherever JavaScript expects a statement, you can also write an expression. 
    Such a statement is called an expression statement. The reverse does not hold: you cannot write a statement where JavaScript expects an expression. 
    For example, an if statement cannot become the argument of a function.    

* CONSOLE.LOG
    args: any type
    returns: undefined
    behaviour: prints args into console

* TEMPORAL DEAD ZONE
    Let and const are:
        - Block scoped.
        - Accessing a var before it is declared has the result undefined; accessing a let or const before it is declared throws ReferenceError;
        - hoisted, but there is a period between entering scope and being declared where they cannot be accessed.

 * HOISTED

    Hoisting is JavaScript's default behavior of moving declarations to the top.
    In JavaScript, a variable can be declared after it has been used.
    JavaScript only hoists declarations, not initializations.
    When JS declares a variable and moves it to the global scope in the creation phase .
    
 * Immediately-Invoked Function Expression (IIFE)
    It is a JavaScript function that runs as soon as it is defined.
    The variable within the expression can not be accessed from outside it.
    ```js 
    (function () {
    statements
    })();
    ```
 * Declared: When you tell JS to make a new variable in memory.
 
 * Defined: When a value is first assigned to a new variable

 * Visible: A variable is visible in a scope if it can be used in that scope.


