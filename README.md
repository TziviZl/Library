# 📚 Digital Library System

This project is a simplified digital library management system demonstrating the use of several **structural design patterns** in C#.

## 🎯 Description

The system allows adding, displaying, and managing books under various categories such as Children, Teens, and Adults, as well as thematic tags like Thriller or Biography.

It integrates key design patterns to ensure flexibility, efficiency, and clean architecture.

---

## 🧠 Implemented Design Patterns

- **Adapter**: Converts standard book display to colored display based on category.
- **Bridge**: Enables switching between different coloring strategies (e.g., background vs. text color).
- **Composite**: Allows nested book categories and recursive handling of books and sub-categories.
- **Decorator**: Adds features like “Rare Book” or “Library Use Only” without modifying the book class.
- **Facade**: Provides a simplified interface (`LibraryFacade`) for borrowing, returning, checking availability, and printing books.
- **Flyweight**: Ensures shared memory for identical books (title, author, category).
- **Proxy**: Manages access permissions — some books are only accessible to premium users.

---

## 🧩 Features

- Add and manage books in various categories.
- Display books in color-coded formats based on category.
- Borrow and return books with availability checks.
- Add optional decorations and metadata to books.
- Control access for regular vs. premium users.

---

## 🚀 How to Use

1. Clone the repository.
2. Open the project in Visual Studio.
3. Run the `Program` class to:
   - Add books (including with decorations).
   - Display books.
   - Test borrowing/returning logic.
   - Verify pattern usage (e.g., Flyweight reuse, Proxy restriction).
   
---

## 🛠 Technologies

- Language: C#
- IDE: Visual Studio
- Concepts: OOP, Design Patterns, Console App

---

## 📌 Notes

This project was created as a design pattern exercise to demonstrate clear and scalable software architecture using C# and .NET principles.

