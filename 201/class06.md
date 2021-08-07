# Object in JS

Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.
Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

## Inherited Properties

Inherited properties of an object are those properties which have been inherited from the object’s prototype, as opposed to being defined for the object itself, which is known as the object’s Own property. To verify if a property is an objects Own property, we can use the hasOwnProperty method.

Property Attributes
Data properties in JavaScript have four attributes.

value: The property’s value.
writable: When true, the property’s value can be changed
enumerable: When true, the property can be iterated over by “for-in” enumeration. Otherwise, the property is said to be non-enumerable.
configurable:If false, attempts to delete the property, change the property to be an access-or property, or change its attributes (other than [[Value]], or changing [[Writable]] to false) will fail.

1. Using the Object literal syntax : Object literal syntax uses the {…} notation to initialize an object an its methods/properties directly.
Let us look at an example of creating objects using this method :
var obj = {
    member1 : value1,
    member2 : value2,
};

2. Object Constructor : Another way to create objects in JavaScript involves using the “Object” constructor. The Object constructor creates an object wrapper for the given value. This, used in conjunction with the “new” keyword allows us to initialize new objects.

3. Constructors: Constructors in JavaScript, like in most other OOP languages, provides a template for creation of objects. In other words, it defines a set of properties and methods that would be common to all objects initialized using the constructor.

4. Prototypes : Another way to create objects involves using prototypes. Every JavaScript function has a prototype object property by default(it is empty by default). Methods or properties may be attached to this property. A detailed description of prototypes is beyond the scope of this introduction to objects.

## Loop in JS

The while statement creates a loop that is executed while a specified condition is true.

The loop will continue to run as long as the condition is true. It will only stop when the condition becomes false.

JavaScript supports different kinds of loops:

- for - loops through a block of code a number of times

- for/in - loops through the properties of an object
- for/of - loops through the values of an iterable object
- while - loops through a block of code while a specified condition is true
- do/while - loops through a block of code once, and then repeats the loop while a specified condition is true

## What is the HTML DOM?

The HTML DOM is a standard object model and programming interface for HTML. It defines:

The HTML elements as objects
The properties of all HTML elements
The methods to access all HTML elements
The events for all HTML elements
