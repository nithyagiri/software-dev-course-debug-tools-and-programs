# 🛠️ Debugging Practice: E-Commerce Application

## 🎯 Objective

Students will apply **debugging tools and strategies** to identify and fix errors in a pre-written JavaScript application.

This exercise emphasizes using:

- The **Console**
- The **Sources tab**
- The **`debugger` statement**
- Practical strategies like **isolating problematic code** and **testing edge cases**

---

## 🛒 Scenario

You are tasked with debugging a simple **JavaScript application** for an **e-commerce platform**.

The application is supposed to:

- Calculate the **total price** of items in a shopping cart
- Apply **discounts**
- Generate a **receipt**

Unfortunately, the application has several bugs that are causing it to malfunction.

---

## 🧩 Your Task

You will:

- 🐛 **Identify and fix errors** using browser developer tools
- 🔍 **Analyze error messages and the call stack** for clues
- 🧪 **Test edge cases** to make sure the program behaves correctly in different scenarios


Errors Found:
1. Loop condition caused undefined item access. Fixed by using i < cartItems.length.
2. 2. Discount rate had no validation. Added range check for 0–1.
3. total.toFixed() threw error when total wasn’t numeric. Added type check.
4. DOM elements could be null. Added conditional element check.

 Debugging Tools Used: 
 - Console tab: Found "Cannot read properties of undefined" error.
- Sources tab: Used breakpoints to watch variable values in calculateTotal().
- Call Stack: Traced flow from generateReceipt() back to applyDiscount().
- Debugger statement: Used to pause loop and check cartItems[i].
---

## 🖥️ Instructions

### 1. Set Up the Debugging Environment

- Open the project’s `index.html` file in your **browser**
- Launch **Developer Tools** using:
  - `F12`, or  
  - `Ctrl+Shift+I` (Windows) / `Cmd+Option+I` (Mac)
  
From there, use the **Console**, **Sources tab**, and **debugger statements** to investigate and fix issues in the JavaScript code.

---

Let me know if you'd like to add starter files, error clues, or a checklist of bugs to find!
