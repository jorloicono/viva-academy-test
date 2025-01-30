# 2. History and Evolution of JavaScript

JavaScript was born to **make the web dynamic**! Below is a brief timeline of its history and evolution:

---

## 🕰️ Origins (1995)
- **Creator**: Brendan Eich, developed for Netscape Communications.
- **Initial Names**: **Mocha** → **LiveScript** → **JavaScript** (to leverage Java’s popularity).
- **Goal**: Add interactivity to web pages (e.g., form validation).

---

## 🔑 Key Milestones
### 1. ECMAScript Standardization (1997)
- JavaScript was standardized by **ECMA International** and renamed **ECMAScript (ES)**.
- **ES1**: First release (1997) with basic features (functions, loops).

### 2. The AJAX Era (2005)
- **AJAX** (Asynchronous JavaScript) enabled dynamic data loading in web apps (e.g., Gmail).

### 3. Rise of jQuery (2006)
- Simplified cross-browser compatibility and DOM manipulation.

### 4. Node.js (2009)
- **Ryan Dahl** created Node.js, bringing JavaScript to **server-side programming**.

### 5. ES6/ES2015 (2015)
- **Revolutionary Update**:
  - `let`/`const`, arrow functions (`=>`), promises, classes.
  - Laid the foundation for modern frameworks (React, Angular, Vue).

---

## 📈 Evolution Timeline
| Year      | Key Development                     |
|-----------|-------------------------------------|
| 1995      | First version (Netscape Navigator 2.0) |
| 1997      | ES1 Standardization                 |
| 2009      | ES5 (JSON support, strict mode)     |
| 2015      | ES6 (Modern syntax)                 |
| 2016+     | Yearly updates (ES2016, ES2017...)  |

---

## 🌍 Impact of JavaScript
- **King of Web Development**: Used by 97% of websites (as of 2023).
- **Versatility**: Powers frontend, backend (Node.js), mobile apps (React Native), and desktop apps (Electron).

---

## Code Example: ES5 vs ES6
```javascript
// ES5 (2009)
var name = "Brendan Eich";
function greet() {
  console.log("Hello, " + name);
}

// ES6 (2015)
const name = "Brendan Eich";
const greet = () => console.log(`Hello, ${name}`);