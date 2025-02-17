
# CSS Nesting Exercise 🌱

## Overview  
In this exercise, you will refactor a given CSS file to make use of **native CSS nesting**. This will help you simplify and organize your styles while keeping everything in standard CSS. You’ll explore the **nested syntax** and understand how to structure styles more logically.

---

## Instructions  

### 1️⃣ Setup  
1. Clone this repository:  
   ```sh
   git clone https://github.com/Vince-Colson-TM/css_nesting_exercise.git
   ```
2. Open `index.html` in a browser.  
3. Open `styles.css` and start refactoring by following the next steps.

---

### 2️⃣ Refactor with Native CSS Nesting  
- Identify **related styles** (e.g., element-specific styles, child elements) that can be grouped together.  
- Use **native CSS nesting** to organize these relationships more logically.  
- Follow the **native CSS nesting syntax**, where nested selectors are placed inside the parent block.

✅ **What to do?**  
- Group the styles for **buttons**, **cards**, and **headings** inside their respective parent selectors.  
- Ensure all elements still look the same after refactoring.  

---

### 3️⃣ Nest Media Queries  
- Use native CSS nesting to **nest media queries** within relevant components.  
- Ensure that the layout is responsive and elements adjust appropriately for **different screen sizes**.  

✅ **What to do?**  
- Move the existing media queries into the relevant **parent selector** (e.g., for `.card` or `.button`).  
- Nest media queries where the styles will apply, maintaining the overall readability of your CSS.

---

### 4️⃣ Refactor Specific Styles with Nesting  
- Simplify specific styles such as **hover states**, **focus styles**, and **active states** by nesting them within the relevant selectors.  
- This will keep your code **cleaner and more maintainable**.  

✅ **What to do?**  
- Nest the `:hover`, `:focus`, and `:active` states for buttons, links, or any other interactive elements within their parent selector.  
- Ensure these states still work properly after the refactor.

---

### 5️⃣ Add and Refactor a New Component  
- Add a new component such as a **footer** or **sidebar**, and apply **native CSS nesting** for related child elements.  
- Make sure that the new styles are properly organized and that the footer or sidebar works correctly.

✅ **What to do?**  
- Create a new component (`.footer` or `.sidebar`) and nest styles for its child elements (e.g., links, lists).  
- Ensure the layout remains correct after the changes.

---

## 🎯 Extra Challenge (Optional)  
Explore **advanced CSS nesting techniques**, such as combining **descendant selectors** and **state-dependent selectors**, to enhance your layout and interactions.

---

## ✅ Learning Outcomes  
By completing this exercise, you will:  
✔ Learn **how to use native CSS nesting** for better style organization.  
✔ Understand **how to structure media queries** within relevant components.  
✔ Discover the benefits of **grouping related styles** together for readability and maintainability.  
✔ Implement **hover, focus, and active states** using nesting for clean code.  
✔ Improve the **responsiveness and maintainability** of your design with native CSS nesting.  
