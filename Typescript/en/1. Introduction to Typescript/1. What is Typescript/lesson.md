
```markdown
# 1. What is TypeScript?

**TypeScript** is a **superset of JavaScript** developed by Microsoft in 2012. It adds **static typing** and **object-oriented programming** features, making code safer and more organized for large-scale projects.

## Key Features:
- **Static Typing**: Type checking at compile time (e.g., `string`, `number`).
- **JavaScript Compatibility**: Any `.js` file can be renamed to `.ts`.
- **Classes & Interfaces**: Full support for OOP concepts.
- **Editor Tooling**: Autocompletion and error highlighting in VS Code.

## Code Example:
```typescript
// TypeScript
function add(a: number, b: number): number {
  return a + b;
}
console.log(add(5, 3)); // Output: 8