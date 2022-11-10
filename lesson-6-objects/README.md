# Unit 2 - Lesson 6: Introduction to JavaScript Objects

## Essential Questions
* What is an _object_ and why are they useful?

An object stores multiple pieces of data about an entity, we can save information about one over arching subject or topic. Within this topic we can define different smaller themes/info about the bigger entity calles properties. These properties are data structures themselves as they are able to store all data types, array, other objects, etc. The information stored within these properties or *keys* are called values

* How do we access object properties? When can we use dot notation and when must we use bracket notation?

To access that properties of an object we use bracket notation *and* dot notation. We can always used bracket notation putting the property inside `""`. We *must* use bracket notation if the key is a number, a string beggining with a non-alphanumeric character. Besides these senarios we can use both whenever.

* What data types can be valid object values in JavaScript? What data types can be valid object keys?

Any data type is valid for object values, keys are only valid as string data types.

* What is the relationship between arrays and objects in JavaScript?

##### Both...

* Both objects
* Both non-primitive (complex) data types
    * They can hold a multitude of values
* Both are data structures
* Both stored in the section of memory called the heap
* Copy/Passed by reference
* Both are mutable
* Use bracket notation to access values
    *  myArr[index = number]
    *  myObj[key = string]
* Both can use methods

 
##### Differences are...

* Arrays use indexes to access values. Objects use keys to access values
* Indexes are integers. Keys are strings.
* Objects can use dot notation to access values
* Arrays are used to make ordered lists
* Objects are used to store related data about an entity

* What does it mean for a property to be _enumerable_?



* What are the ways that we can iterate over objects?
* How can we copy the properties from one object to another?

## Vocabulary
* key
* value
* property (key-value pair)
* method
* dot notation
* bracket notation
* object literal (object initializer)
* enumerable
* shallow copy
* deep clone

## Key Operators and Methods
* `delete`
* `in`
* `for... in` loop
* `Object.keys`
* `Object.assign`
* `hasOwnProperty`
 
## Learning Assignments
* **Article:** [Working with Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects) on MDN **(stop at _Creating New Objects_ section)**
* **Article:** JavaScript Weekly: [An Introduction to Iteration and Enumerability](https://medium.com/launch-school/javascript-weekly-an-introduction-to-iteration-and-enumerability-70bb1054064a)
* **Book:** Eloquent JavaScript - [Chapter 4 - Data Structures: Objects and Arrays](https://eloquentjavascript.net/04_data.html) **(stop at _The Lycanthrope's Log_ section)**
* **Article:** [Understanding Date and Time in JavaScript](https://www.digitalocean.com/community/tutorials/understanding-date-and-time-in-javascript)

**You need to understand how to use the following operators and methods:**
* **Documentation:** [`in` operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/in) on MDN
* **Documentation:** [`delete` operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete) on MDN
* **Documentation:** [`for ... in`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in) on MDN
* **Documentation:** [`Object.keys()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys) on MDN
* **Documentation:** [`Object.assign`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign) on MDN
* **Documentation:** [`hasOwnProperty`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty) on MDN
