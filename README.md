Here are the **frontend development interview questions you have practiced so far**, along with their **answers**:

---

### **📌 HTML Interview Questions**  

✅ **1. What are the three main types of HTML elements?**  
✔ **Answer:**  
There are three types of HTML elements:  
1. **Block-level elements**: Start on a new line and take up the full width of the container.  
   - **Examples**: `<div>`, `<p>`, `<h1>` to `<h6>`, `<section>`, `<article>`  
2. **Inline elements**: Stay within the same line and take up only as much width as needed.  
   - **Examples**: `<span>`, `<a>`, `<b>`, `<i>`  
3. **Inline-block elements**: Behave like inline elements but allow width and height to be set.  
   - **Examples**: `<img>`, `<button>`, `<input>`  

✅ **2. What is the difference between `<div>` and `<span>`?**  
✔ **Answer:**  
- **`<div>`** is a **block-level** element used for grouping elements and creating layouts.  
- **`<span>`** is an **inline** element used to style a small portion of text inside a block.  

✅ **3. What is Semantic HTML?**  
✔ **Answer:**  
Semantic HTML refers to using meaningful HTML elements that describe their content.  
- **Examples**: `<header>`, `<footer>`, `<article>`, `<section>`, `<nav>`, `<aside>`.  
- It **improves SEO**, **accessibility**, and **code readability**.  

✅ **4. Why is Semantic HTML important?**  
✔ **Answer:**  
- Improves **SEO (Search Engine Optimization)**.  
- Helps **screen readers** understand content better.  
- Makes the code **more readable and maintainable**.  

✅ **5. What is the difference between `id` and `class` attributes?**  
✔ **Answer:**  
- **`id`**: Unique identifier for an element (`id="header"`). Used only **once** per page.  
- **`class`**: Can be used on **multiple elements** (`class="btn btn-primary"`).  

✅ **6. What is the difference between `<section>`, `<article>`, and `<div>`?**  
✔ **Answer:**  
- **`<section>`**: Groups related content together.  
- **`<article>`**: Represents a **self-contained** piece of content (e.g., a blog post).  
- **`<div>`**: A generic container with no meaning, used for styling/layout.  

✅ **7. What are the different types of lists in HTML?**  
✔ **Answer:**  
1. **Ordered list (`<ol>`)** – Numbered list (1, 2, 3, …).  
2. **Unordered list (`<ul>`)** – Bulleted list.  
3. **Description list (`<dl>`)** – Used for key-value pairs.  

✅ **8. What is the difference between `<strong>` and `<b>`?**  
✔ **Answer:**  
- **`<strong>`**: Gives text **strong importance** (used for accessibility & SEO).  
- **`<b>`**: Simply **bolds** the text without adding importance.  

✅ **9. What is the difference between `<em>` and `<i>`?**  
✔ **Answer:**  
- **`<em>`**: Gives text **emphasis** (used for accessibility & SEO).  
- **`<i>`**: Simply **italicizes** the text.  

✅ **10. What is the difference between `<iframe>` and `<embed>`?**  
✔ **Answer:**  
- **`<iframe>`**: Embeds another webpage inside a page.  
- **`<embed>`**: Embeds external content like videos or PDFs.  

---

### **🎨 CSS Interview Questions**  

✅ **11. What are the three types of CSS?**  
✔ **Answer:**  
1. **Inline CSS** – Written inside an HTML tag (`<p style="color:red;">Hello</p>`).  
2. **Internal CSS** – Inside a `<style>` tag in the `<head>` section.  
3. **External CSS** – In a `.css` file linked using `<link>` in HTML.  

✅ **12. Why is External CSS better than Inline CSS?**  
✔ **Answer:**  
- **Separation of concerns** (keeps HTML & CSS separate).  
- **Easier to maintain** and **reuse** across multiple pages.  

✅ **13. What is the difference between `relative`, `absolute`, and `fixed` positioning?**  
✔ **Answer:**  
- **Relative**: Positioned **relative to its normal position**.  
- **Absolute**: Positioned **relative to its nearest positioned ancestor**.  
- **Fixed**: Positioned **relative to the viewport (doesn’t move when scrolling)**.  

✅ **14. Why does `flex flex-col sm:flex-row` behave differently on small and large screens?**  
✔ **Answer:**  
- `flex-col` (default) → Items are stacked **vertically** on small screens.  
- `sm:flex-row` → On `sm` (640px+), items **align horizontally**.  

✅ **15. What is the difference between `visibility: hidden` and `display: none`?**  
✔ **Answer:**  
- `visibility: hidden` → The element is **still there** but **not visible**.  
- `display: none` → The element is **removed from the layout** completely.  

---

### **⚡ JavaScript Interview Questions**  

✅ **16. How did you learn frontend development?**  
✔ **Answer:**  
"I learned frontend development through **YouTube**, **Google Docs**, and **ChatGPT**. I also built projects using **HTML, CSS, JavaScript, and React** to practice."  

✅ **17. What is the difference between `var`, `let`, and `const`?**  
✔ **Answer:**  
- **`var`**: Function-scoped, can be re-declared and updated.  
- **`let`**: Block-scoped, can be updated but not re-declared.  
- **`const`**: Block-scoped, **cannot** be re-declared or updated.  

✅ **18. What is the difference between `==` and `===`?**  
✔ **Answer:**  
- **`==` (Loose equality)**: Compares **values only** (`5 == "5"` → `true`).  
- **`===` (Strict equality)**: Compares **values + data types** (`5 === "5"` → `false`).  

✅ **19. What is the difference between `null` and `undefined`?**  
✔ **Answer:**  
- **`null`**: Assigned value meaning "empty" or "nothing".  
- **`undefined`**: A variable that has been declared but **not assigned** a value.  

✅ **20. What is local storage and session storage in JavaScript?**  
✔ **Answer:**  
- **Local Storage**: Stores data **permanently** until manually cleared.  
- **Session Storage**: Stores data **only for the current session** (clears when the page is closed).  

---

### **🔗 Git & GitHub Interview Questions**  

✅ **21. How to fix `error: failed to push some refs to GitHub`?**  
✔ **Steps you followed:**  
1️⃣ Checked **git branch**:  
   ```sh
   git branch -M main
   ```  
2️⃣ Added and committed files:  
   ```sh
   git add .
   git commit -m "Initial commit"
   ```  
3️⃣ Pushed the code:  
   ```sh
   git push -u origin main
   ```  

---

### **🔥 What’s Next?**  
✅ **Do you want to practice more advanced questions** on **JavaScript, React, or system design?** 🚀
