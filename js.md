[Main Website](https://cheatsheetshub.github.io/)
# Python

* Python is an interpreted, high-level and general-purpose, dynamically typed programming language

* It is also Object oriented, modular oriented and a scripting language.

* In Python, everything is considered as an Object.

* A python file has an extension of .py

* Python follows Indentation to separate code blocks instead of flower brackets({}).

* We can run a python file by the following command in cmd(Windows) or shell(mac/linux).

    `$ python <filename.py>` or `$ python3 <filename.py>`

## Menu

 - [Create and execute a program](python.md#Create-and-execute-a-program)
 - [Basic Datatypes](python.md#Basic-Datatypes)
 - [Keywords](python.md#Keywords)
 - [Operators](python.md#Operators)
 - [Basic Data Structures](python.md#Basic-Data-Structures)
 -- [Dictionary](python.md#Dictionary)
 -- [List](python.md#List)
--  [Tuple](python.md#Tuple)
-- [Set](python.md#Set)
-- [Conditional branching](python.md#Conditional-branching)
 - [Loops](python.md#Loops)
 --[While loop](python.md#While-loop)
 --[For Loop](python.md#For-Loop)
- [Function](python.md#Function-definition)
 

## Create and execute a program
By default, python doesn't require any imports to run a python file.

1. Open up a terminal/cmd
1. Create the program: nano/cat > nameProgram.py
1. Write the program and save it
1. python nameProgram.py

<br>

# Global 

### Properties

| Data Type | Description |
| --------- | ----------- |
| Object.length | length is a property of a function object, and indicates how many arguments the function expects, i.e. the number of formal parameters. This number does not include the rest parameter. Has a value of 1. |
| Object.prototype  | Represents the Object prototype object and allows to add new properties and methods to all objects of type Object. |


<br>

## Methods of the Object constructor
<br>

- As of python3.8 there are 35 keywords

| Keyword | Description  | Category |
|---------- | ---------- | --------- | 
| Object.assign     | Copies the values of all enumerable own properties from one or more source objects to a target object. method is used to copy the values of all enumerable own properties from one or more source objects to a target object. It will return the target object  | (target, ...sources)|
| Object.create     | Creates a new object with the specified prototype object and properties. The object which should be the prototype of the newly-created object. | MyObject |
| Object.defineProperty     | Adds the named property described by a given descriptor to an object. | obj, prop, descriptor |
| Object.defineProperties     | Adds the named properties described by the given descriptors to an object. | obj, props |
| Object.entries  | Returns an array containing all of the [key, value] pairs of a given object's own enumerable string properties.| | obj |
|Object.entries      | Returns an array containing all of the [key, value] pairs of a given object's own enumerable string properties. | obj |
| Object.freeze       | Freezes an object: other code can't delete or change any properties. | obj |
| Object.getOwnPropertyDescriptor  | Returns a property descriptor for a named property on an object. | obj, prop |
| Object.getOwnPropertyDescriptors | Returns an object containing all own property descriptors for an object. | obj |
| Object.getOwnPropertyNames | Returns an array containing the names of all of the given object's own enumerable and non-enumerable properties. | obj |
| Object.getOwnPropertySymbols | Returns an array of all symbol properties found directly upon a given object. | obj |
| Object.getPrototypeOf | Returns the prototype of the specified object. | obj |
| Object.is | Compares if two values are the same value. Equates all NaN values (which differs from both Abstract Equality Comparison and Strict Equality Comparison). | value1, value2 |
| Object.isExtensible | Determines if extending of an object is allowed. | obj | 
| Object.isFrozen | Determines if an object was frozen. | obj |
| Object.isSealed | Determines if an object is sealed. | obj |
| Object.keys | Returns an array containing the names of all of the given object's own enumerable string properties. | obj |
| Object.preventExtensions | Prevents any extensions of an object. | obj |
| Object.seal | Prevents other code from deleting properties of an object. | obj |
| Object.setPrototypeOf | Sets the prototype (i.e., the internal [[Prototype]] property). | obj, prototype |
| Object.values | Returns an array containing the values that correspond to all of a given object's own enumerable string properties. | obj |

<br>

## Properties
Object instances and Object prototype object (Object.prototype.property or Object.prototype.method()
Properties
<br>


| Operator | Description |
|-|-|
|  obj.constructor 	|  Specifies the function that creates an object's prototype. |
|  obj.__proto__ 	|  Points to the object which was used as prototype when the object was instantiated.|
# Methods

| obj.hasOwnProperty | Returns a boolean indicating whether an object contains the specified property as a direct property of that object and not inherited through the prototype chain. | 
|--|--|
| prototypeObj.isPrototypeOf | Returns a boolean indicating whether the object this method is called upon is in the prototype chain of the specified object. |
| obj.propertyIsEnumerable | Returns a boolean indicating if the internal ECMAScript [[Enumerable]] attribute is set. | 
|obj.toLocaleString  | Calls toString(). |
| obj.toString() | Returns a string representation of the object. |
|object.valueOf() |Returns the primitive value of the specified object.v|




