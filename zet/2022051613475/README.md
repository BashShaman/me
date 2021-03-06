# Variables

There are *instance variables* (the state of an object) and *local variables* (are defined inside methods). Both an instance variable and a local variable can be defined without assignment. In such a case an instance variable will be automatically assigned to the default value for its type. These are: `0` for integer types including `character` type, `0.0` for floating point types, `false` for `boolean` type and `null` for any reference variable. Local variables cannot be used before assignment. Such an attempt will lead to the error. Method parameters are considered as local variables, they cannot be defined without assignment as it's mandatory to put the appropriate number of arguments wiht the appropriate types to any method call.

There are *primitive variables* and *object references*. There are 8 types of primitive variables: `boolean`, `char`, `byte`, `short`, `int`, `long`, `float`, `double`. A primitive variable contains the sequence of bytes which represents its value. A reference variable contains the sequence of bytes which represents **the link** to the object (the way to get this object) in **the memory heap**. An array itself is an object in the heap and it can contain both references and primitives. Each object of an array can be thought as a distinct variable of the array's type. 

A variable can be thought as a container with a particular size. It's save to assign a byte value to an int variable but the opposite is forbidden (spillage). A floating point value cannot be assigned to an integer variable (all data after the dot will be lost). Java compiler won't allow yout to assign you the link to an instance of the `Dog` class to a variable of the type `Cat` (dogs certainly cannot meow).

If a reference variable was declared without asignment it's value is `null` (it contains *a null reference*). It's possible to assign `null` to any reference variable to sever it's connection to the object in the heap. If an object has no links to it, it becomes a candidate to be garbage collected. 

    #java #variable #primitive #reference
