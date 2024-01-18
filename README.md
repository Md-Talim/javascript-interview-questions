# Basics of JavaScript

## 1. What is JavaScript

JavaScript is a programming language that allows us to add dynamic and interactive features to web pages. It can manipulate HTML, CSS, and other web technologies to create responsive and user-friendly websites. JavaScript can also run on other platforms, such as servers, mobile devices, and desktop applications.

## 2. Explain the difference between `let`, `const`, and `var`.

The difference between `let`, `const` and `var` keywords is mainly related to their scope, redeclaration, and reassignment. Here is a summary of their differences:

| var | let | const |
| --- | --- | --- |
| 🌐 Global Scoped | 📦 Block Scoped | 📦 Block Scoped |
| ✅ Can be redeclared | ⛔ Cannot be redeclared within the same scope | ⛔ Cannot be redeclared within the same scope |
| ✅ Can be re-assigned | ✅ Can be re-assigned | ⛔ Cannot be re-assigned |

## 3. How does hoisting work in JavaScript?

Hoisting refers to the process where the interpreter appears to move the declarations to the top of the code before execution. Variables can thus be referred to even before they are declared in JavaScript.

**Important Note:** JavaScript only hoists declarations, not initializations. The variables will be undefined until the line where it is initialized is read.

```jsx
console.log(num); // Throws error if let or const
let num = 80;     // With var undefined is printed
```
