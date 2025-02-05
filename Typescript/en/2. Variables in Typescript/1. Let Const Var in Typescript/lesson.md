
---

```markdown
# 1. Let, Const, Var in TypeScript

In TypeScript, `let`, `const`, and `var` are used for variable declarations, but **static typing** adds extra safety compared to JavaScript.

---

## 🔍 Differences (In TypeScript)
| Feature             | `var`                          | `let`                          | `const`                        |
|---------------------|--------------------------------|--------------------------------|--------------------------------|
| **Scope**           | Function-scoped               | Block-scoped                  | Block-scoped                  |
| **Type Annotation** | `var age: number = 25;`       | `let name: string = "Alice";` | `const PI: number = 3.14;`     |
| **Reassign**        | Allowed                       | Allowed                       | Not allowed (primitives)      |
| **Redeclare**       | Allowed                       | Not allowed                   | Not allowed                   |

---

## 📝 Examples & Explanation

### 1. `let` (With Type Annotation)
```typescript
let count: number = 10;
count =