
---

```markdown
# 2. History and Evolution of TypeScript

**TypeScript** was created to address JavaScript’s limitations and manage large-scale projects. Below is a brief history:

---

## 🕰️ Origins (2012)
- **Creator**: **Anders Hejlsberg** at Microsoft.
- **Initial Goal**: Add **static typing** and **scalability** to JavaScript.
- **First Release**: October 2012 (Version 0.8).

---

## 🔑 Key Milestones
### 1. TypeScript 1.0 (2014)
- **Static Typing** and **Class** support.
- Introduction of **Generics**.

### 2. TypeScript 2.0 (2016)
- **Nullable Types** (`null` and `undefined` management).
- **Union/Intersection Types** (`string | number`).

### 3. TypeScript 3.0 (2018)
- **Tuple Types**, **Project References**.
- Deep integration with **React/Angular**.

### 4. TypeScript 4.0+ (2020-Present)
- **Variadic Tuple Types**.
- **Template Literal Types** (`type Color = 'red' | 'blue'`).

---

## 📈 Evolution Timeline
| Year       | Key Updates                              |
|------------|------------------------------------------|
| 2012       | First public release (v0.8)             |
| 2014       | Version 1.0 (Static Typing)             |
| 2016       | Version 2.0 (Nullable Types)            |
| 2020       | Version 4.0 (Modern Feature Extensions) |

---

## 🌍 Impact & Adoption
- **Default in Enterprise Apps**: Used in Angular, NestJS, React.
- **Influence on JavaScript Ecosystem**: Features like classes were tested in TypeScript before ES6+.
- **Stack Overflow Survey 2023**: Ranked among top 5 most loved languages.

---

## Code Example: TypeScript vs JavaScript
```typescript
// TypeScript (with Interface and Types)
interface User {
  name: string;
  age: number;
}

function greet(user: User): string {
  return `Hello, ${user.name}!`;
}