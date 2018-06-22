**Program to an interface, not an implementation.**

Don't declare variables to be instances of particular concrete classes. Instead, commit only to an interface defined by an abstract class. By abstracting the process of object creation, these patterns give you different ways to associate an interface with its implementation transparently at instantiation. Creational patterns ensure that your system is written in terms of interfaces, not implementations.

Because inheritance exposes a subclass to details of its parent's implementation, it's often said that "inheritance breaks encapsulation" [Sny86]. The implementation of a subclass becomes so bound up with the implementation of its parent class that any change in the parent's implementation will force the subclass to change

Reuse: Composition, Inherientence, Parameterized Types (generics and templates)

Favor object composition over class inheritance.

One cure for this is to inherit only from abstract classes, since they usually provide little or no implementation.

Reuseby inheritance makes it easier to make new components that can be composed with old ones. Inheritance and object composition thus work together.

a receiving object delegates operations to its delegate. (use Has-A. Composition)

Delegation is a good design choice only when it simplifies more than it complicates.