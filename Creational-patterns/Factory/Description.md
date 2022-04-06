# Factory

La lógica de creación se vuelve 
más convolucionada.

Creación de un objeto de manera completa, no en partes como en el Builder.

La creación completa del objeto puede delegarse a un método separado (Factory Method) o en una clase aparte (Factory) o crear una jerarquía de factories (Abstract Factories)

Factory es un componente responsable únicamente de la creación completa, no por partes, de objetos.

## Factory Method

It's not a good idea to create an initializer with more and more optional parameters
An alternative to handle many ways of initilize an object by creating abstract methods

Statics methods that create objects
## Factory
Any entity that can take care of object creation

The implementation of the single responsability principle

It's not necessary to add the methods as static

A different class that has factory methods. 

## Abstract Factory

Not only have a hierarchy of the classes 
but a hierarchy of the factories

Needs the abstract for strict typing since in Python is optional to have it

Hierarchies of hierarchies can be used to create related objects. 