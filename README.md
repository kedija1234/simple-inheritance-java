# Simple Inheritance Example in Java

## 📌 Project Description

This is a simple Java project that demonstrates the concept of **inheritance** in object-oriented programming (OOP). In this project, we have two classes:

- **Animal** (Superclass)
- **Dog** (Subclass)

The **Dog** class inherits from the **Animal** class and utilizes the **`super()`** constructor to initialize the properties from the **Animal** class. The project also shows how a subclass can add its own methods, such as the `bark()` method in the **Dog** class, while inheriting methods like `eat()` from the **Animal** class.

This project is an excellent way to understand the basics of **inheritance**, **method overriding**, and **constructor inheritance** in Java.

---

## 🔧 Key Concepts Covered

- **Inheritance**: The `extends` keyword allows the **Dog** class to inherit the properties and methods of the **Animal** class.
- **Constructor Inheritance**: The subclass calls the superclass constructor using the `super()` keyword.
- **Method Inheritance**: The `Dog` class inherits the `eat()` method from the **Animal** class.
- **Subclass-specific Methods**: The **Dog** class adds its own method `bark()`.
- **Code Reusability**: The **Dog** class can reuse the `eat()` method from **Animal**, demonstrating **code reuse**.

---

## 📁 Project Structure

```plaintext
simple-inheritance-java/
 ├── Animal.java    # Superclass (base class) with common functionality
 ├── Dog.java       # Subclass (derived class) that inherits from Animal
 └── MainApp.java   # Main class to test the inheritance and methods
