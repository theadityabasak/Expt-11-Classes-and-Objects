# Expt-11-Classes-and-Objects
# AppUSed: VS Code
# Theory
## Definition
Object-Oriented Programming (OOP) is a programming principle centered around the concept of "objects."

### What is a Class?
Class is basically a framework or blueprint which we use to create objects. It encapsulates data and functions that operate on the data. Objects share similarities to its class. For eg children and thier parents where children could be considered objects of the parent class.

For example:
#include <iostream>
using namespace std;

class Dog {
public:
    string name;
    int age;

    void bark() {
        cout << name << " Woof!" << endl;
    }
};
### What is an Object?
An object is basically an instance of a class. It is a self-contained unit that contains both data and methods. The data (attributes) represents the state of the object, while the methods (functions) define its behavior. For eg, in a class Car, an object could be a specific car with features like color and model, and operations like starting engine, driving.
An Object has two defining features:

Attributes: These are the properties of an object. They represent the characteristics of the object. For eg, if you have a Car object, its attributes might include color, model, year etc. Attributes define what the object knows about itself.

Methods: These are the functions or behaviors that an object can perform. They define what the object can do or what operations can be performed on it. For the Car object, methods might include start_engine(), drive(), and apply_brakes(). Methods define what actions the object can take or how it can interact with other objects.

For Example: Creating an object of class Dog:
int main() {
    Dog myDog;
    myDog.name = "Buddy";
    myDog.age = 3;

    myDog.bark();

    return 0;
}
## Principles of OOP in C++
1. Encapsulation
Encapsulation is the concept of bundling data and methods that operate on that data within a single unit, typically a class. It hides the internal state of the object from the outside world and only exposes a controlled interface.
Example: In C++, encapsulation is achieved using classes. Data members (attributes) are kept private or protected, and access to these members is provided through public methods (getters and setters).
2. Inheritance
Inheritance allows a class (derived class) to inherit properties and behaviors (methods) from another class (base class). This promotes code reusability and establishes a hierarchy between classes.
Polymorphism
Polymorphism allows objects of different classes to be treated as objects of a common base class. The most common use of polymorphism is to call methods on objects of derived classes through base class pointers or references, enabling dynamic method binding.
4. Abstraction
Abstraction focuses on hiding the complex implementation details and showing only the necessary features of an object. It simplifies interactions with objects by exposing only the relevant methods and properties.

## Advantages of Using Classes and Objects
Modularity: Classes and objects promote modularity in programming by dividing a program into distinct, manageable sections. Each class represents a specific component or concept.

Reusability: Classes allow code reuse through inheritance and composition. Once a class is defined, it can be reused in multiple programs or projects, reducing duplication and effort.

Maintainability: By encapsulating data and methods within classes, code becomes easier to maintain. Changes to a class can be made in one place, and all objects of that class will automatically reflect the changes.

Scalability: Object-oriented design supports scalability by allowing the addition of new classes and methods without affecting existing code. This makes it easier to expand and enhance programs over time.

Real-World Modeling: Classes and objects align closely with real-world concepts and entities, making it easier to model complex systems and understand the relationships between different components.

# Algorithms
## Program1
Start 1.Define Class:

Define a class named Student.
Declare public member variables:
string name
int age
string branch
float result
string year In main() Function:
2.Create Objects:

Create an object student1 of type Student.

Create an object student2 of type Student.

Create an object student3 of type Student.

Initialize student1:

Set student1.name to "Akshit".

Set student1.age to 18.

Set student1.branch to "ENTC".

Set student1.result to 8.00.

Set student1.year to "Second".

3.Display Details for student1:

Print "Student1 details:"
Print student1.name
Print student1.branch
Print student1.year
Print student1.result
4.End

# Proram2: method inside class
tart 2.Define Class:

Class Student:
Attributes:
string name
int age
string branch
float result
string year 3.Method:
void printYear()
Print the year of study in the format: "I am studying in [year] year" In main() Function:
4.Create and Initialize student1:

Create an object student1 of type Student.

Set student1.name to "Akshit".

Set student1.age to 18.

Set student1.branch to "ENTC".

Set student1.result to 8.00.

Set student1.year to "Second".

5.Display Details for student1:

Print "Student1 details:".
Print student1.name.
Print student1.branch.
Print student1.result.
Call student1.printYear() to print the year of study.
6.End

# Program3: method outside class
tart 2.Define Class Student:

Attributes:
string name
int age
string branch
float result
string year 3.Methods:
void printYear()
Print the message: "I am studying in [year] year" In main() Function:
4.Create and Initialize student1:

Create an object student1 of type Student.

Set student1.name to "Akshit".

Set student1.age to 18.

Set student1.branch to "ENTC".

Set student1.result to 8.00.

Set student1.year to "Second". 5.Display Details for student1:

Print "Student1 details:"

Print student1.name

Print student1.branch

Print student1.result

Call student1.printYear() to print "I am studying in Second year"

6.End

# Conclusion
We learnt to use the concepts of Class and Objects.

