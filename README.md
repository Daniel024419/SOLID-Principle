# SOLID-Principle

The SOLID principles are a set of five design principles in object-oriented programming that, when followed, can lead to more understandable, flexible, and maintainable code. These principles were introduced by Robert C. Martin, also known as "Uncle Bob."

SOLID Acronym
S - Single Responsibility Principle (SRP)

A class should have only one reason to change, meaning it should only have one job or responsibility. This promotes cohesion and reduces the impact of changes.
O - Open/Closed Principle (OCP)

Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification. This means you should be able to add new functionality without changing existing code, promoting robustness and preventing regression bugs.
L - Liskov Substitution Principle (LSP)

Objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program. This ensures that a subclass can stand in for its parent class without causing errors, promoting reliable inheritance.
I - Interface Segregation Principle (ISP)

No client should be forced to depend on methods it does not use. This principle promotes the creation of smaller, more specific interfaces rather than large, general-purpose ones, reducing dependencies and increasing modularity.
D - Dependency Inversion Principle (DIP)

High-level modules should not depend on low-level modules. Both should depend on abstractions (e.g., interfaces). Abstractions should not depend on details; details should depend on abstractions. This principle promotes decoupling and makes the system more flexible and easier to maintain.
