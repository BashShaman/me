# Characteristics of Objects

An object is an entity which has 4 main characteristics:

 * identity
 * type
 * state
 * behavior

## Identity

Every object has identity. That means that any object of some type is distinguishable from any other object of this type and any object of another type. Any object is living in its own memory location and the address of the first byte of this location gives the object its identity. There is no way to work directly with these addresses in Java for a programmer. Every object in Java has a hash code. The hash code *almost* gives identity to the object as two different objects can have the same hash code.

## Type

In Java names of classes are used as types of reference variables. Explore the example below:

~~~Java
Cat c = new Cat();
~~~

The type of the variable `c` is the name of the class `Cat`.

## State

Class definition in Java can contain a list of attributes. Every instance of a particular class will necessarily have the attributes defined inside the class. Any two objects can have different values for these attributes. **The state** of an object is the combination of the values of all its attributes (private and public). Unlike identity, which is permament, the state of an obect can change over time.

## Behavior

The behavior of an object is determined by the class of this object. Unlike values of attributes, every instance of a prticular class shares methods with other instances of the class. Public methods and attributes of a class form *the interface* of this class (what an instance of the class can do). The implementation (how object works internally) must be hidden to the user.

        #java #object #identity #state #behavior #type
