# designpatterns
contains: 
  - code
  - poster
  - book
  - a quick rundown of the patterns
  - a comprehensive rundown with uml diagram
## quick summary

### Strategy Pattern:

Summary: Defines a family of algorithms, encapsulates each one, and makes them interchangeable.  
Use Case: Ideal for situations where you need to select an algorithm at runtime, such as varying behavior in a game or different sorting strategies in an application.


### Observer Pattern:

Summary: Establishes a one-to-many relationship between objects, ensuring that when one object changes state, all its dependents are notified and updated.  
Use Case: Used when you need to notify multiple objects about changes, such as updating user interfaces, handling event-driven systems, or implementing publish-subscribe mechanisms.


### Decorator Pattern:

Summary: Dynamically adds responsibilities to objects without altering their code.  
Use Case: Useful when you need to extend an object's behavior with flexible and reusable options, like adding features to a text editor or enhancing a beverage order.


### Factory Method Pattern:

Summary: Provides an interface for creating objects, allowing subclasses to alter the type of objects created.  
Use Case: Employed when you want to delegate the responsibility of object creation to subclasses, enabling customized object instantiation.


### Singleton Pattern:

Summary: Ensures that a class has only one instance and provides a global point of access to that instance.  
Use Case: Valuable for managing shared resources such as configuration settings, logging, and database connections.


### Command Pattern:

Summary: Encapsulates a request as an object, allowing for parameterization of clients with requests and supporting undoable operations.  
Use Case: Effective when you need to decouple sender and receiver objects, implement transactional systems, or create macro recording/playback functionality.


### Adapter Pattern:

Summary: Makes the interface of an existing class compatible with another interface.  
Use Case: Useful for integrating legacy code, incorporating third-party libraries, or adapting interfaces to work with existing systems.


### Facade Pattern:

Summary: Provides a simplified interface to a complex subsystem.  
Use Case: Beneficial for simplifying the interaction with intricate systems, such as libraries, frameworks, or multi-layer architectures.


### Template Method Pattern:

Summary: Defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps.  
Use Case: Ideal when you want to establish a common structure with customizable parts, enabling consistency in algorithms with varying implementations.


### Iterator Pattern:

Summary: Provides a way to access elements of an aggregate object sequentially without exposing its underlying representation.  
Use Case: Simplifies the traversal of collections or complex data structures, enhancing iteration flexibility and code clarity.


### Composite Pattern:

Summary: Composes objects into tree structures to represent part-whole hierarchies.  
Use Case: Valuable for creating complex structures made up of individual and composite objects, such as graphical user interfaces, document structures, or organizational hierarchies.


### State Pattern:

Summary: Allows an object's behavior to change when its internal state changes.  
Use Case: Appropriate for situations where an object exhibits different behaviors based on its internal state, simplifying complex conditional logic.


### Proxy Pattern:

Summary: Provides a surrogate or placeholder for another object to control access to it.  
Use Case: Useful for scenarios like lazy loading of resources, access control, logging, or monitoring, where you need to manage access to an object.


### Compound Patterns:

Summary: Combines multiple design patterns to solve complex problems.  
Use Case: When dealing with multifaceted challenges that can be effectively addressed by leveraging the synergies of various design patterns working together.  



## Comprehensive summary


### Strategy Pattern
- **Summary**: In the Strategy Pattern, you have different strategies, much like various ways of playing a video game. Depending on the game situation, you can choose the best strategy. This pattern allows you to switch between different ways of doing something in a flexible way.
- **Example**: Think of a game character that can use different weapons like a sword, a bow, or magic. Depending on the enemy or situation, you select the best weapon to fight.
- **UML Diagram**: ![Strategy Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/3/39/Strategy_Pattern_in_UML.png)

### Observer Pattern
- **Summary**: The Observer Pattern is like a sports scoreboard. When a team scores a point, the scoreboard updates automatically for everyone to see. In programming, this pattern lets objects watch and react when something changes.
- **Example**: Imagine a weather app that displays the current temperature. Whenever the temperature changes, the app updates automatically to show the new temperature.
- **UML Diagram**: ![Observer Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Observer_w_update.svg/500px-Observer_w_update.svg.png)

### Decorator Pattern
- **Summary**: The Decorator Pattern is akin to adding layers of customization to your computer or smartphone. You can enhance its features without altering the core device. In programming, this pattern allows you to add new features to objects dynamically.
- **Example**: Consider an image editing app where you can keep adding filters, stickers, or text to an image without changing the original image.
- **UML Diagram**: ![Decorator Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Decorator_UML_class_diagram.svg/500px-Decorator_UML_class_diagram.svg.png)

### Factory Method Pattern
- **Summary**: Think of ordering different types of customized pizzas online. You choose the kind you want, and it's made for you. In programming, this pattern abstracts object creation, so you don't need to know how it's done.
- **Example**: Suppose you want to create different types of vehicles like cars or bikes without worrying about the specifics of how each vehicle is built. The factory method pattern takes care of it.
- **UML Diagram**: ![Factory Method Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/FactoryMethod_UML_class_diagram.svg/500px-FactoryMethod_UML_class_diagram.svg.png)

### Singleton Pattern
- **Summary**: Imagine a manager's office with only one key, and everyone shares it. In programming, this pattern ensures there's only one instance of a class, like a global manager for handling tasks.
- **Example**: You have a game with a high score manager. The singleton pattern ensures there's only one instance to manage and display the highest score.
- **UML Diagram**: ![Singleton Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Singleton_UML_class_diagram.svg/500px-Singleton_UML_class_diagram.svg.png)

### Command Pattern
- **Summary**: It's like having a remote control for your TV. When you press a button, it sends a command to the TV to do something. In programming, this separates the sender and receiver of commands.
- **Example**: You're building a home automation system. Each button on a remote control sends a command to control lights, TV, or music.
- **UML Diagram**: ![Command Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Command_pattern.svg/500px-Command_pattern.svg.png)

### Adapter Pattern
- **Summary**: Think of using a plug adapter to charge your devices in different countries. It helps you connect new things to old systems. In programming, it makes two incompatible interfaces work together.
- **Example**: You have an old printer with a parallel port, but your computer uses USB. An adapter allows you to connect the printer to your modern computer.
- **UML Diagram**: ![Adapter Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Adapter_UML_class_diagram.svg/500px-Adapter_UML_class_diagram.svg.png)

### Facade Pattern
- **Summary**: It's like ordering food from a restaurant. You talk to a waiter who takes your order and handles the kitchen work. In programming, it simplifies complex systems by providing a unified interface.
- **Example**: You're developing a computer game. The facade pattern simplifies interactions with various game engines, graphics, and sound systems.
- **UML Diagram**: ![Facade Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Facade_UML_class_diagram.svg/500px-Facade_UML_class_diagram.svg.png)

### Template Method Pattern
- **Summary**: This pattern is like following a recipe to bake different types of cakes. The recipe has a fixed structure - first, you prepare the batter, then bake it, and finally, decorate it. You can customize the type of cake and decoration, but the basic steps remain the same. In programming, this pattern defines a template for an algorithm with fixed steps, allowing subclasses to provide their implementations for specific parts.
- **Example**: Think of a game framework that provides a basic game structure. Subclasses can implement their own game logic while following the framework's predefined steps.
- **UML Diagram**: ![Template Method Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Template_Method_UML.svg/500px-Template_Method_UML.svg.png)

### Iterator Pattern
- **Summary**: Think of reading through a book page by page. You don't need to see the entire book at once; you go through it step by step. In programming, this pattern helps you access elements of a collection one at a time without worrying about how the collection is organized.
- **Example**: Think of a music playlist. The iterator pattern allows you to play songs one by one without knowing the playlist's internal structure.
- **UML Diagram**: ![Iterator Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/Iterator_UML_class_diagram.svg/500px-Iterator_UML_class_diagram.svg.png)

### Composite Pattern
- **Summary**: Picture a company's organizational chart. It shows the hierarchy of employees and teams. In programming, the composite pattern lets you treat individual objects and groups of objects (composites) uniformly.
- **Example**: You can manipulate individual shapes and groups of shapes (composites) in a drawing application.
- **UML Diagram**: ![Composite Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/W3sDesign_Composite_Design_Pattern_UML.jpg/800px-W3sDesign_Composite_Design_Pattern_UML.jpg)

### State Pattern
- **Summary**: Think of a traffic light - red, yellow, green. It changes its behavior based on its state. In code, this pattern makes an object act differently depending on its condition.
- **Example**: You're modeling a vending machine. Depending on its state (e.g., "no money," "selecting a product," "dispensing"), it performs different actions.
- **UML Diagram**: ![State Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/W3sDesign_State_Design_Pattern_UML.jpg/800px-W3sDesign_State_Design_Pattern_UML.jpg)

### Proxy Pattern
- **Summary**: The Proxy Pattern is like having a representative or placeholder for an object. It controls access to the real object. In programming, this pattern can be used for various purposes, such as lazy loading, access control, or monitoring.
- **Example**: Imagine a virtual bookshelf where you see book covers. When you click on a book cover, the actual book is loaded. The book covers are proxies for the real books.
- **UML Diagram**: [Proxy Pattern UML Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Proxy_pattern_diagram.svg/500px-Proxy_pattern_diagram.svg.png)

### Compound Pattern
- **Summary**: The Compound Pattern isn't a standalone pattern but a combination of two or more patterns. It's like creating a recipe by mixing various ingredients. In programming, this combines patterns to solve complex problems.
- **Example**: You're designing a game engine. You might use a combination of patterns like the Factory Method, Singleton, and Observer to handle game object creation and events.
- **UML Diagram**: Compound patterns do not have specific UML diagrams as they involve multiple patterns.


