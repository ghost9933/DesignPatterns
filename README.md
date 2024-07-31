# DesignPatterns
Intro to Software Design patterns
#  Java Implementations

This repository contains Java implementations of various design patterns and examples to illustrate its use and benefits.

## Implemented Patterns

So far, this repository covers the following design patterns:

- **Strategy Pattern**
  - Location: `strategy/`
  - The strategy pattern defines a family of algorithms, encapsulates each one, and makes them interchangeable. Strategy lets the algorithm vary independently from clients that use it.

- **Adapter Pattern**
  - Location: `adapter/`
  - The adapter pattern converts the interface of a class into another interface clients expect. Adapter lets classes work together that couldn't otherwise because of incompatible interfaces.

- **Observer Pattern**
  - Location: `observer/`
  - The observer pattern defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.

## Getting Started

To run any of the pattern implementations:

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/design-patterns-java.git
   ```

3. Navigate to the pattern directory you are interested in:
  ```
    cd design-patterns-java/strategy
  ```
5. Compile and run the Java files (assuming you have JDK installed):
   ```
   javac StrategyExample.java
   java StrategyExample
   ```
