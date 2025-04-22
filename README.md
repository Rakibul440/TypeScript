# TypeScript
TypeScript is a **strongly typed superset of JavaScript** that compiles to plain JavaScript. It's widely used in modern web development — especially in large codebases and frameworks like React, Angular, and Next.js.

Here’s a quick breakdown to understand TypeScript better:

---

## 🔧 What TypeScript Adds to JavaScript

### ✅ Static Typing
You can define what types your variables, parameters, and return values should be:

```ts
let name: string = 'Alice';
let age: number = 25;
let isOnline: boolean = true;
```

---

### ✅ Type Inference
TypeScript is smart and can guess types when possible:

```ts
let count = 10; // TypeScript infers `number`
```

---

### ✅ Interfaces & Types
Define shapes for objects, functions, etc.

```ts
interface User {
  id: number;
  name: string;
  isAdmin?: boolean; // optional
}
```

---

### ✅ Enums
For readable sets of constant values:

```ts
enum Role {
  Admin,
  User,
  Guest,
}
```

---

### ✅ Generics
Write reusable functions and components:

```ts
function identity<T>(arg: T): T {
  return arg;
}
```

---

## 🔍 TypeScript vs JavaScript

| Feature            | JavaScript | TypeScript |
|--------------------|------------|------------|
| Static typing       | ❌ No       | ✅ Yes      |
| Compile-time errors | ❌ No       | ✅ Yes      |
| IDE support         | ✅ Some     | ✅ Excellent |
| Used in large apps  | ✅ Often    | ✅ Preferred |

---

## 🚀 Why Use TypeScript?

- **Fewer runtime errors**
- **Better autocompletion & IntelliSense**
- **Self-documenting code**
- **Scales better for teams/projects**

---

## 🛠 Getting Started

```bash
# Install globally
npm install -g typescript

# Compile a TypeScript file
tsc file.ts
```

Or use it in a project:

```bash
# Initialize a project with tsconfig.json
tsc --init
```

---

