# Frontend Interview Questions  

## Table of Contents  
1. [HTML Questions](#html-questions)  
2. [CSS Questions](#css-questions)  
3. [JavaScript Questions](#javascript-questions)  
4. [React.js Questions](#reactjs-questions)  
5. [Frontend System Design](#frontend-system-design)  
6. [Performance Optimization](#performance-optimization)  
7. [Resources & Practice](#resources--practice)  

---

Here are all the **frontend development interview questions** you've practiced so far, plus some extra ones to help you improve:  

---

### **📌 HTML Interview Questions**  
1️⃣ What are the three main types of HTML elements?  
2️⃣ What is the difference between `<div>` and `<span>`?  
3️⃣ What is Semantic HTML? Can you give some examples?  
4️⃣ What are the benefits of using Semantic HTML?  
5️⃣ What is the difference between `id` and `class` attributes?  
6️⃣ What is the difference between `<section>`, `<article>`, and `<div>`?  
7️⃣ What are the different types of lists in HTML?  
8️⃣ What is the difference between `<strong>` and `<b>`?  
9️⃣ What is the difference between `<em>` and `<i>`?  
🔟 What is the difference between `<iframe>` and `<embed>`?  

---

### **🎨 CSS Interview Questions**  
1️⃣ What are the different types of CSS?  
2️⃣ What is the difference between **inline, internal, and external CSS**?  
3️⃣ What is the difference between `relative`, `absolute`, and `fixed` positioning?  
4️⃣ What is Flexbox, and how does it work?  
5️⃣ What is CSS Grid, and how is it different from Flexbox?  
6️⃣ How does `z-index` work in CSS?  
7️⃣ What is the difference between `em`, `rem`, `px`, and `%` in CSS?  
8️⃣ What is the difference between `visibility: hidden` and `display: none`?  
9️⃣ What are pseudo-classes and pseudo-elements? Can you give examples?  
🔟 What is the difference between `nth-child` and `nth-of-type`?  

---

### **⚡ JavaScript Interview Questions**  
1️⃣ What is the difference between `var`, `let`, and `const`?  
2️⃣ What are primitive and non-primitive data types in JavaScript?  
3️⃣ What is the difference between `==` and `===`?  
4️⃣ What are arrow functions, and how do they differ from regular functions?  
5️⃣ What is the difference between synchronous and asynchronous JavaScript?  
6️⃣ What is the event loop in JavaScript?  
7️⃣ What is the difference between `null` and `undefined`?  
8️⃣ What are promises, and how do they work?  
9️⃣ What is the difference between `map()`, `forEach()`, and `filter()`?  
🔟 What is local storage and session storage in JavaScript?  

---

### **⚛️ React.js Interview Questions**  
1️⃣ What is React, and why is it used?  
2️⃣ What is the difference between class components and functional components?  
3️⃣ What are React hooks? Can you name some important hooks?  
4️⃣ What is `useState`, and how does it work?  
5️⃣ What is `useEffect`, and when is it used?  
6️⃣ What is React Router, and how does it work?  
7️⃣ What is the difference between `props` and `state` in React?  
8️⃣ What is the virtual DOM in React




## HTML Questions  

# **HTML Basics:**  
🔹 **Question 1: What are the different types of HTML elements?**  
HTML elements define the structure of a webpage. They are mainly categorized into three types: Block-level elements, Inline elements, and Inline-block elements. Block-level elements, like `<div>` and `<p>`, take up the full width and start on a new line.
Inline elements, like <span> and <a>, only take up as much space as necessary and don’t start on a new line. Inline-block elements, like `<img>` and `<button>`, behave like inline elements but allow setting width and height.
There are three main types of HTML elements: Block-level, Inline, and Inline-block elements.

Block-level elements start on a new line and take up the full width of their container. Examples include <div>, <p>, <h1> to <h6>, and <section>.
Inline elements do not start on a new line and take up only as much width as their content requires. Examples include <span>, <a>, and <b>.
Inline-block elements behave like inline elements, but they allow setting width and height like block elements. An example is the <img> tag.

### **Question 2: What is the difference between `inline`, `block`, and `inline-block` elements?**  
In HTML, elements are categorized into three types based on how they behave in a document: Block-level, Inline, and Inline-block elements.

Block-level elements start on a new line and take up the full width of their container.
Examples: `<div>`, `<p>`, `<h1>` to `<h6>`, `<section>`, `<article>`.

Inline elements do not start on a new line and take up only as much space as their content needs.
Examples: `<span>`, `<a>`, `<strong>`, `<em>` .

Inline-block elements behave like inline elements (staying in line with other elements) but allow setting width and height like block elements.
Examples:  `<img>`, `<button>`, <`input>`.

Great! Here's your next question. 😊  

### **Question 3: What is the difference between `<div>` and `<span>` in HTML?**  
In HTML, the <div> tag is a block-level element that takes up the full width of its container, creating a section on a new line. It's typically used to group larger content sections. On the other hand, the <span> tag is an inline element that only takes as much width as necessary and stays inline with surrounding elements. The <div> is used for creating layout structures, while <span> is used for styling small portions of text or inline content without affecting the page layout.

examples:
`<div style="background: lightgray;">This is a div</div>`
`<span style="color: red;">This is a span</span>`

Awesome! 

### **Question 4: What are semantic HTML elements, and why are they important?**
"Semantic HTML elements are HTML tags that carry meaning and help define the structure of a webpage. Examples include `<header>`, `<footer>`, `<article>`, and `<nav>`. These elements make websites more accessible, improve SEO, and make the code easier to maintain. Using semantic HTML helps search engines understand the content and improves the overall user experience."

You're on the right track! Let’s refine and expand on the answer to make it clearer and more comprehensive:

---

### **Answer:**

**Semantic HTML elements** are HTML tags that carry meaning about the content inside them. They help define the structure and content of a webpage, making it easier for both browsers and developers to understand. These elements clearly describe their content, as opposed to **non-semantic elements** like `<div>` and `<span>`, which don't indicate anything about the content they contain.

---

### **Examples of Semantic HTML Elements:**
- **`<header>`**: Represents the introductory content or navigational links of a webpage.
- **`<footer>`**: Defines the footer section of a webpage, usually containing copyright, links, or other information.
- **`<article>`**: Used for self-contained content, like a news article or blog post.
- **`<section>`**: Represents a section of content within a webpage, such as a group of related content.
- **`<nav>`**: Represents navigation links.
- **`<main>`**: Indicates the main content of the document, excluding headers, footers, and sidebars.
- **`<aside>`**: Defines content that is tangentially related to the content around it (e.g., a sidebar).
- **`<figure>`** and **`<figcaption>`**: Used for images and their captions.

---

### **Why Are Semantic HTML Elements Important?**

1. **Improved Accessibility**:  
   Semantic elements make websites more accessible to people with disabilities by providing clear structure, especially for screen readers. For example, `<nav>` helps screen readers recognize navigation sections.

2. **Better SEO (Search Engine Optimization)**:  
   Search engines can better understand and index the content on your page when semantic elements are used. For example, search engines prioritize the content inside `<article>` and `<header>` because they are meaningful.

3. **Easier to Maintain**:  
   Developers can easily understand the structure and purpose of a webpage when semantic HTML is used, making code easier to maintain.

4. **Clearer Code Structure**:  
   It improves the readability of the code by indicating the role of different content sections, making it easier for other developers to work with the code.

---

### **Summary:**
Using **semantic HTML elements** makes your webpage more accessible, SEO-friendly, and easier to maintain. These elements provide meaning and structure, improving both the development process and the user experience.

---
*"Semantic HTML elements are HTML tags that carry meaning and help define the structure of a webpage. Examples include `<header>`, `<footer>`, `<article>`, and `<nav>`. These elements make websites more accessible, improve SEO, and make the code easier to maintain. Using semantic HTML helps search engines understand the content and improves the overall user experience."*

---


### **Question 5: What is the difference between HTML and HTML5?**  
### **HTML vs. HTML5**:

- **HTML** (Hypertext Markup Language) is the standard language used to create webpages. It provides the structure for web pages.
  
- **HTML5** is the latest version of HTML. It introduces new features and elements to improve functionality, performance, and mobile responsiveness. Some key differences:
  
  1. **New Elements**:
     - HTML5 introduced new semantic elements like `<article>`, `<section>`, `<nav>`, `<header>`, `<footer>`, and `<aside>`, which help structure the page better for both users and search engines (SEO).
  
  2. **Multimedia Support**:
     - HTML5 added native support for audio and video using the `<audio>` and `<video>` elements. This eliminates the need for plugins like Flash.
  
  3. **Local Storage**:
     - HTML5 provides local storage and session storage, allowing websites to store data on the user’s browser, making it possible to create offline apps.
  
  4. **Improved Forms**:
     - HTML5 introduced new input types (like `email`, `date`, `number`, etc.) and form attributes (like `placeholder`, `autofocus`, etc.) to improve user experience and form validation.
  
  5. **Geolocation**:
     - HTML5 introduced geolocation API, which allows websites to access a user's geographical location (with permission).
  
  6. **Canvas and SVG**:
     - HTML5 introduced the `<canvas>` element, allowing dynamic, scriptable rendering of 2D shapes and bitmap images. It also supports SVG (Scalable Vector Graphics) for creating vector-based graphics.

### **In short**:  
HTML5 is an updated version of HTML that enhances multimedia, mobile capabilities, and offers better structure and functionality.
...
## CSS Questions  

### **Question 6: What are the different types of CSS?**  
"There are three types of CSS: Inline CSS, Internal CSS, and External CSS. Inline CSS is written directly inside an HTML tag using the style attribute and is used for small, quick styling changes. Internal CSS is written inside a <style> tag in the <head> section of an HTML document and is used when styling a single page. External CSS is written in a separate .css file and linked to the HTML using the <link> tag, making it ideal for large projects where styles need to be applied across multiple pages."
...  

## JavaScript Questions  
### What is the difference between `==` and `===`?  
**In JavaScript, `==` (loose equality) and `===` (strict equality) are used for comparison.**  

- **Loose equality (`==`)** compares only values and performs **type coercion**, meaning JavaScript automatically converts one data type to another if necessary.  
  ```js
  let a = 5; 
  let b = "5"; 
  console.log(a == b); // true (string "5" is converted to number 5)
  ```

- **Strict equality (`===`)** compares both values and data types **without performing type coercion**. The data types must be the same for it to return `true`.  
  ```js
  console.log(a === b); // false (number 5 is not the same type as string "5")
  ```

### What is the difference between function declarations and function expressions in JavaScript? 
✅ **"A function declaration uses the `function` keyword and a function name. It is hoisted, meaning it can be called before its declaration in the code."**  

### Example:
```javascript
greet("Prashant"); // Works because of hoisting

function greet(name) {
  return "Good morning, " + name;
}
```
✅ **"A function expression is defined using the `function` keyword, either with a name (named function expression) or without a name (anonymous function expression). It is not hoisted, meaning it cannot be invoked before its declaration in the code."**  

### Example:
```javascript
greet("PK"); // ❌ Error: Cannot access 'greet' before initialization

const greet = function (name) {
  return "Good morning, " + name;
};

console.log(greet("PK")); // ✅ Works after declaration
```
Here are examples of **named function expressions** and **anonymous function expressions**:  

### **Named Function Expression:**  
- The function has a name (`greet`).  
- The name can be used for recursion or debugging.  
```javascript
const greet = function greetFunction(name) {
  return "Hello, " + name;
};

console.log(greet("Prashant")); // ✅ Output: Hello, Prashant
```
Even though the function has a name (`greetFunction`), it can only be accessed via the variable `greet`.

---

### **Anonymous Function Expression:**  
- No function name is provided.  
- It is assigned directly to a variable.  
```javascript
const greet = function (name) {
  return "Hello, " + name;
};

console.log(greet("Prashant")); // ✅ Output: Hello, Prashant
```
Since it has no name, it cannot reference itself inside the function (useful for recursion).  
### **When to Use Named vs. Anonymous Function Expressions**  

✅ **Use Named Function Expressions when:**  
1. **Debugging**: If an error occurs, the function name appears in stack traces, making debugging easier.  
2. **Recursion**: If the function needs to call itself inside, a named function expression is required.  
3. **Readability**: Improves code readability by making the function’s purpose clearer.  

**Example:**  
```javascript
const factorial = function fact(n) {
  if (n === 0) return 1;
  return n * fact(n - 1); // Using the function's own name for recursion
};

console.log(factorial(5)); // ✅ Output: 120
```
Here, `fact(n)` is used to call itself inside the function.

---

✅ **Use Anonymous Function Expressions when:**  
1. **Short-lived functions**: If a function is used immediately and not referenced elsewhere.  
2. **Event handlers & Callbacks**: Common in event listeners, setTimeout, or array methods.  
3. **Arrow Functions**: Modern JavaScript often prefers arrow functions for brevity.  

**Example (Event Listener):**  
```javascript
document.getElementById("btn").addEventListener("click", function () {
  console.log("Button clicked!");
});
```
Here, the function doesn't need a name because it's just handling an event.

---

📌 **Best Practice:**  
- Use **named functions** for better debugging and recursion.  
- Use **anonymous functions** for simple one-time use cases like event handlers or callbacks.  


### Key Differences from Function Declarations:
- Function expressions are **not hoisted**.
- Can be **anonymous** (without a function name).
- Usually assigned to a variable.

...
### Explain event delegation in JavaScript.  
...


