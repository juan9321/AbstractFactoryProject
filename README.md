Abstract Factory Pattern - Project Description
This project demonstrates the Abstract Factory design pattern, which is used to create objects from different families of products without specifying their concrete classes. The main goal is to provide an interface for creating related objects while ensuring the products belong to the same family.

Structure
Product: Represents a hierarchy of product classes and interfaces, each specific to a different type of product. Each family of products has its own implementation.

Abstract Factory: The AbstractFactory interface defines methods to create different types of products. It provides a common interface for object creation, ensuring consistency across the product family.

Concrete Factories: Concrete classes like ConcreteFactory1 and ConcreteFactory2 implement the AbstractFactory interface. They are responsible for creating specific families of products.

Concrete Products: Classes like ProductA1, ProductA2, ProductB1, and ProductB2 implement product interfaces defined by the Abstract Factory. These classes provide specific variations depending on which factory creates them.

Client: The client interacts with the factory using the AbstractFactory interface. This allows the client to create objects in a flexible manner, without needing to know the concrete classes of the products.

Source: Refactoring Guru - Abstract Factory
