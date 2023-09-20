# designpatterns
contains: 
  - code
  - poster
  - book
  - a quick rundown of the patterns
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
