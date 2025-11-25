# 📅 Day 1 – JavaScript Basics

Welcome to **Day 1** of my JavaScript learning journey!
Today I covered the *history of JavaScript*, different ways of *integrating JavaScript into web pages*, and some *limitations* of the language.

## 🕰️ 1. Evolution of JavaScript

Here’s the timeline of how JavaScript came into existence:

* In the early 1990s, the web started using a language called **ECMA Script**.
* In 1995, **Netscape** launched a browser named *Netscape Communicator*.
* Netscape hired **Brendan Eich** to create a scripting language for the browser.
* Eich created **Mocha**, which was renamed **LiveScript**.
* Netscape handed LiveScript to **Sun Microsystems**, who renamed it **JavaScript**.
* JavaScript and Java are *not* related — the name was only a marketing decision.
* In 2002, Netscape gave JavaScript rights to **ECMA**, which now maintains it.
* Each JavaScript version follows the ECMA Script standard:


<table align="center">
  <tr>
    <th>JavaScript Version</th>
    <th>ECMA Name</th>
  </tr>
  <tr>
    <td>JavaScript 2015</td>
    <td>ES5 / ES2015</td>
  </tr>
  <tr>
    <td>Modern versions</td>
    <td>ES6, ES7, … ES22 (2022)</td>
  </tr>
</table>


## 🌐 2. Integrating JavaScript into HTML

JavaScript can be added to a webpage in **three different ways**:


### **✔ 1. Inline Technique**

* JavaScript is written directly inside an HTML element.
* Fastest approach but **cannot be reused**.


### **✔ 2. Embedded Technique**

* JavaScript is placed inside a `<script>` tag in the HTML document.
* Can be added inside `<head>` or `<body>`.
* Multiple MIME types exist:

  * `text/javascript`
  * `type="module"` for ES modules
  * Compiler-specific MIME types (e.g., Babel)

**Strict Mode**

* JavaScript is not strictly typed.
* Enable strict mode with:
  `"use strict";`
* Helps catch silent errors and makes code safer.

**Legacy Browser Support**

* Scripts could be wrapped inside HTML comments to hide them from old browsers.

### **✔ 3. External File Technique**

* JavaScript can be written in external `.js` files.
* Reusable across pages.
* Slight drawback: increases number of HTTP requests → adds load time.
* Code can be minified for production.


## ⚠️ Drawbacks of JavaScript

Some inherent issues with JavaScript include:

* Not a strongly typed language
* Type inconsistencies require explicit validation
* Not fully object-oriented
* Limited OOP features
* Extensibility challenges
* Some security concerns
* No dynamic polymorphism

> 💡 **Modern alternative:**
> Developers often use **TypeScript** for stronger typing and better structure.
> TypeScript is *not* a replacement — it compiles *to* JavaScript.


## 📘 Summary of Day 1

Today I learned:

* How JavaScript was invented and standardized
* The three ways to add JavaScript to a webpage
* The purpose of strict mode
* Pros and cons of inline vs embedded vs external scripts
* Basic limitations of JavaScript
* How modern developers handle these limitations

---
