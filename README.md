# Duck Interfaces

This repository demonstrates the use of interfaces in Java by modeling various types of ducks and their behaviors.

## Overview

The project defines different duck behaviors using interfaces and implements these behaviors across various duck classes. This approach showcases how interfaces can be utilized to design flexible and extensible code structures.

## Contents

The repository includes the following Java files:

- **Duck.java**: An abstract class representing a generic duck.
- **FlyBehavior.java**: An interface defining the flying behavior.
- **Fly.java**: A class implementing `FlyBehavior` for ducks that can fly.
- **NotFly.java**: A class implementing `FlyBehavior` for ducks that cannot fly.
- **SwimBehavior.java**: An interface defining the swimming behavior.
- **Swim.java**: A class implementing `SwimBehavior` for ducks that can swim.
- **MallardDuck.java**: A class extending `Duck`, representing a mallard duck.
- **RedHeadDuck.java**: A class extending `Duck`, representing a redhead duck.
- **RubberDuck.java**: A class extending `Duck`, representing a rubber duck.
- **DecoyDuck.java**: A class extending `Duck`, representing a decoy duck.
- **ModelDuck.java**: A class extending `Duck`, representing a model duck.
- **Main.java**: The main class to test and demonstrate the duck behaviors.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/eesha-barad/Duck-Interfaces.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Duck-Interfaces
   ```

3. Compile the Java files:

   ```bash
   javac *.java
   ```

4. Run the `Main` class:

   ```bash
   java Main
   ```

This will execute the program and display the behaviors of different duck types.

## Concepts Demonstrated

- **Interfaces**: Defining contracts for behaviors (`FlyBehavior`, `SwimBehavior`) that can be implemented by various classes.
- **Abstract Classes**: Creating a base `Duck` class with common properties and methods, allowing subclasses to inherit and customize behavior.
- **Polymorphism**: Utilizing interfaces and abstract classes to enable objects to take on multiple forms, promoting flexible and reusable code.

This project serves as a practical example of applying object-oriented programming principles in Java to model real-world entities and their behaviors.
