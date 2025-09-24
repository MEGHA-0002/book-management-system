# Book Management System (JavaScript)

A simple JavaScript project that shows how to use **classes, constructors, getters, and setters**.  
This program stores information about books and allows safe updating of book prices.

---

## 🚀 Features
- Store book details: **title, author, price**
- Get book title and author using getter methods
- Update book price using a setter method (only if it's a **number greater than 0**)
- Print book details

---

## 📝 Example Code
```javascript
let myBook = new Book("The Alchemist", "Paulo Coelho", 299);

// Invalid price update
myBook.setPrice(-50);    // ❌ Invalid
myBook.setPrice("free"); // ❌ Invalid

// Valid price update
myBook.setPrice(350);    // ✅ Price updated

// Print final details
myBook.printDetails();
