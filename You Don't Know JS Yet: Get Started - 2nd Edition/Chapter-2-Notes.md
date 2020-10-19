
### Arrays 
JS Arrays can hold any type of value. primitive or object, including other arrays!

### Declaring and Using Variables
Don't be afraid of using Var, it has it places for uses. I will learn all of it's features and use them when it's safe to do so.

### Functions
- Another meaning of function in javascript is procedure. A procedure is a collection of statements that can be called multiple times. 
- A parameter insides a function acts as a local variable

### Comparisons
(===) disallows for any sort of type conversion(coercion), other JS Comparisons do allow it. 
- type coercion is the automatic or implicit conversion of values from one data type to another (such as strings to numbers).
- When comparing NaN user Number.isNaN(..) and for -0 comparioson use the Object.is(..)

### Coercive Comparisons
- (==) loose equality operator. Creator of JS Languaged has said that it was a big mistake because its poorly designed, dangerous and bug ridden
- Loose equality operator preferes primitive numeric comparisons.

### How We Organize in JS
- the two major patterns for organize code: classes and modules. they're not mutually exclusive.
#### Classes
- its a type of custom data structure that includes both data and behaviors that operate on that data. In order to get a value that we can use, a class needs to be created as an instance and we must use the _new_ keyword
- behavior methods can only be called on instances, so we need to assign a new NoteBook to a var and then we can call .addPage(..) or page.print() on those instances. can't target the actual Notebook or page classes
#### Class Inheritance
- 
