**B. KISS (Keep It Simple, Stupid):**
The KISS principle implies that the system should be as simple and understandable as possible. In this code, we try to keep the logic simple, using simple data structures and clear methods. For example, the ViewAll method simply prints information about the zoo to the console making the code clear and easy to understand.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L31).

**Single Responsibility Principle:** Each class is responsible for only one piece of functionality. For example, the Zoo, Animal, Enclosure, Employee, and Food classes are responsible for managing their respective zoo entities.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L31).

**Open/Closed Principle:** Classes are written to be open to extension but closed to modification. For example, you can easily add new methods or properties to classes without changing existing code.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L31).

**Liskov Substitution Principle:** Classes can be replaced by instances of their subtypes without affecting the correctness of the program. For example, if we have a method that takes an object of type Animal, we can pass in any class that inherits from Animal, such as Lion or Tiger.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L182).

**D. YAGNI (You Aren't Gonna Need It):** The YAGNI principle suggests not adding functionality that is not currently needed. There is no obvious violation of this principle in the code, since functionality is added only when necessary (for example, methods for adding, removing, and viewing elements).
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L372).

**E. Composition Over Inheritance:** The principle is that it is better to use object composition than class inheritance. There are no examples of inheritance in the code above, but there are examples of object composition, for example, Zoo contains the lists Animals, Enclosures, Employees, and Foods.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L31).

**F. Program to Interfaces not Implementations:** The code uses an interface-based approach, which allows for more flexible dependency management and easier testing. For example, methods for working with Zoo objects accept the Zoo interface instead of a specific implementation, making it easy to replace implementations as needed.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L116).

**G. Fail Fast:** The principle is to detect and respond to errors as early as possible. The code contains user input checks and checks for null references, which corresponds to the Fail Fast principle.
You can marvel at the butt here [Program.cs](KPZ-LAB-01/KPZ-LAB-01/Program.cs#L116).



