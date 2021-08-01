# Expressions and operators : 

# - Operators
JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence. 

# 1. Assignment operators :
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

# 2. Comparison operators :

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons.

# 3. Arithmetic operators :
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).

# 4.  Logical operators :

Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following tabl

# 5 . String operators :
In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.

# 6. Loops :
 are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false when analysed. A loop will continue running until the defined condition returns false 


 # -  while loop
The while loop starts by evaluating the condition. If the condition is true, the statement(s) is/are executed. If the condition is false, the statement(s) is/are not executed. After that, while loop ends.

Here is the syntax for while loop:

Syntax:
while (condition)

{

  statement(s);

}

# - Do-while loop
The do...while loop is closely related to while loop. In the do while loop, the condition is checked at the end of the loop.

Here is the syntax for do...while loop:

Syntax:
 do {

   *Statement(s);*

} while (*condition*);

# - for-in loop
The for...in statement iterates over the enumerable properties of an object, in arbitrary order. For each distinct property, statements can be executed.

for (variable in object) {
...
}
--- 


# - Expressions
An expression is any valid unit of code that resolves to a value.
Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.
The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven. 

# 1. Primary expressions :
Basic keywords and general expressions in JavaScript.

this
Use the this keyword to refer to the current object. In general, this refers to the calling object in a method. Use this either with the dot or the bracket notation:

# 2. Grouping operator :
The grouping operator ( ) controls the precedence of evaluation in expressions. For example, you can override multiplication and division first, then addition and subtraction to evaluate addition first.

# 3. Left-hand-side expressions :
Left values are the destination of an assignment.
new
You can use the new operator to create an instance of a user-defined object type or of one of the built-in object types. 