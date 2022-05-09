# Singleton

For some components it only makes sense to have one in the system. 

A component which is instantiated once

Use a decorator to avoid that the initializer is called more than once. It is possible to use a Metaclass too

## Monostate

any instance will have the same data. 

Different realizations
custom allocator, decorator, metaclass

It has some testability issues