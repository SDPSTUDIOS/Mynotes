kotlin was introduced in I/O 2017
In Kotlin we do not need to explicitly state the datatype of the variable

Why google advocating Kotlin for Android development
- Null safety
- Conciseness
- Full interoperability with Java
- Coroutines for async work

Kotlin feature
- Semicolon is optional
- datatype after variable name
- Class members public unless declared private
- Null safety
- Data classes

Repeat loops are native for only Kotlin

### Null Safety
- In kotlin a variable cannot be default to null
	- `var number_of_students: Int? = null` this is accepted
	- `var number_of_students: Int = null` No accepted
- null safety operator (?)
	- `number_of_students = number_of_students?.dec()`
- Throws null exception operator (!! - Double bang)
	- `val len = s!!.length`
- Elvis operator (?:)
	- `val result = a ?: b`
	- This means: "if `a` is not null, use `a`; otherwise use `b`."
## When to use what

- Define a broad spectrum of behaviour or type? InInterface
- Will the behaviour be specific to that type? Consider a class
- Need to inherit from muliple classes? Consider refactoring code to see if some behaviour can be info an interface
- You can extend only one class
## Assignment Hint

- Use Null safety
- 